---
layout: homepage
---

## About Me

I am currently an honorary postdoctoral fellow in the [BTM](https://biomedirobotics.com/) group, Department of Mechanical and Automation Engineering, The Chinese University of Hong Kong, and also a postdoctoral fellow in [Multi-scale Medical Robotics Center](https://www.mrc-cuhk.com/), both directed by [Prof. Kwok Wai Samuel Au](https://www4.mae.cuhk.edu.hk/peoples/au-kwok-wai-samuel/). Prior to my PhD study, I received B.E. and M.E. degrees at Harbin Institute of Technology, China. In the third year, I was visiting the group of [Prof. Hartmut Geyer](https://www.cs.cmu.edu/~hgeyer/) at Carnegie Mellon University, USA. Besides, I was visiting the Chair for Computer Aided Medical Procedures & Augmented Reality [(CAMP)](https://www.cs.cit.tum.de/camp/start/), supervised by [Prof. Nassir Navab](https://www.professoren.tum.de/en/navab-nassir), at Technical University of Munich, Germany, from July 2023 to Jan 2024.

My research interests include 1) Developments of robotic surgical and medical systems and related algorithms; 2) Developments of nuanced manipulation skills on (deformable) objects and their applications in surgery and service; 3) Developments of agile locomotion systems and related algorithms / their applications on biomechanics.


## News
- **[Jun. 2024]** One paper about restoring a needle's visibility is accepted to IEEE Transactions on Instrumentation & Measurement.
- **[Jun. 2024]** One paper about explaining kangaroo rat's tail motion is accepted to Integrative and Comparative Biology. This is our first paper in **Robotics for Biology**!
- **[May 2024]** One paper about autonomous robotic surgery is accepted to RSS 2024.
- **[May 2024]** I was recognized for distinguished service as an Outstanding Reviewer for the IEEE Robotics and Automation Letters.
- **[Jan. 2024]** One paper about interactive navigation using large models is accepted to ICRA 2024.
- **[Jan. 2024]** One paper is accepted to ACC 2024.
- **[Jan. 2024]** One paper about learning-based MPC for DOM is accepted to RA-L.
- **[Dec. 2023]** One workshop proposal about agile movement (II) is accepted to ICRA 2024.
- **[Sept. 2023]** One paper is accepted to Humanoids 2023.
- **[Sept. 2023]** One paper about hybrid inertial appendage is accepted to RA-L.
- **[Sept. 2023]** One paper about learning from intuitive teleoperation is accepted to ISER 2023.
- **[Jul. 2023]** One paper is accepted to T-RO.
- **[Jun. 2023]** One paper is accepted to IROS 2023.
- **[May 2023]** One paper about large-scale cloth manipulation is accepted to CASE 2023.
- **[Jan. 2023]** Two papers are accepted to ICRA 2023.
- **[Dec. 2022]** One workshop proposal about agile movement is accepted to ICRA 2023.
- **[Jun. 2022]** One paper about nonholonomic vehicle navigation is accepted to T-MECH.
- **[May 2022]** One paper is accepted to T-MECH.
- **[Apr. 2022]** One paper about null space avoidance theory is accepted to T-CST.
- **[Feb. 2022]** One paper is accepted to ACC 2022.
- **[Jul. 2021]** I defended my Ph.D. dissertation with the committee members: Prof. Yunhui Liu, Prof. Kwok Wai Samuel Au, Prof. Tat Ming Lau, and Prof. Marco Hutter.

  ## News
<ul id="news-list">
    <li class="news-item">**[Jun. 2024]** One paper about explaining kangaroo rat's tail motion is accepted to Integrative and Comparative Biology. This is our first paper in **Robotics for Biology**!</li>
    <li class="news-item">**[May 2024]** One paper about autonomous robotic surgery is accepted to RSS 2024.</li>
    <li class="news-item">**[May 2024]** I was recognized for distinguished service as an Outstanding Reviewer for the IEEE Robotics and Automation Letters.</li>
    <li class="news-item">**[Jan. 2024]** One paper about interactive navigation using large models is accepted to ICRA 2024.</li>
    <li class="news-item">**[Jan. 2024]** One paper is accepted to ACC 2024.</li>
    <li class="news-item">**[Jan. 2024]** One paper about learning-based MPC for DOM is accepted to RA-L.</li>
    <li class="news-item">**[Dec. 2023]** One workshop proposal about agile movement (II) is accepted to ICRA 2024.</li>
    <li class="news-item">**[Sept. 2023]** One paper is accepted to Humanoids 2023.</li>
    <li class="news-item">**[Sept. 2023]** One paper about hybrid inertial appendage is accepted to RA-L.</li>
    <li class="news-item">**[Sept. 2023]** One paper about learning from intuitive teleoperation is accepted to ISER 2023.</li>
    <li class="news-item">**[Jul. 2023]** One paper is accepted to T-RO.</li>
    <li class="news-item">**[Jun. 2023]** One paper is accepted to IROS 2023.</li>
    <li class="news-item">**[May 2023]** One paper about large-scale cloth manipulation is accepted to CASE 2023.</li>
    <li class="news-item">**[Jan. 2023]** Two papers are accepted to ICRA 2023.</li>
    <li class="news-item">**[Dec. 2022]** One workshop proposal about agile movement is accepted to ICRA 2023.</li>
    <li class="news-item">**[Jun. 2022]** One paper about nonholonomic vehicle navigation is accepted to T-MECH.</li>
    <li class="news-item">**[May. 2022]** One paper is accepted to T-MECH.</li>
    <li class="news-item">**[Apr. 2022]** One paper about null space avoidance theory is accepted to T-CST.</li>
    <li class="news-item">**[Feb. 2022]** One paper is accepted to ACC 2022.</li>
    <li class="news-item">**[Jul. 2021]** I defended my Ph.D. dissertation with the committee members: Prof. Yunhui Liu, Prof. Kwok Wai Samuel Au, Prof. Tat Ming Lau, and Prof. Marco Hutter.</li>
</ul>

<div class="show-more-btn" onclick="toggleNews()">Show More</div>

<script>
    function toggleNews() {
        const newsItems = document.querySelectorAll('.news-item');
        const showMoreBtn = document.querySelector('.show-more-btn');
        let showing = false;

        newsItems.forEach((item, index) => {
            if (index >= 10) {
                if (item.classList.contains('show')) {
                    showing = true;
                }
                item.classList.toggle('show');
            }
        });

        showMoreBtn.textContent = showing ? 'Show More' : 'Show Less';
    }

    document.addEventListener('DOMContentLoaded', () => {
        const newsItems = document.querySelectorAll('.news-item');
        newsItems.forEach((item, index) => {
            if (index < 10) {
                item.classList.add('show');
            }
        });
    });
</script>

{% include_relative _includes/publications.md %}

{% include_relative _includes/services.md %}

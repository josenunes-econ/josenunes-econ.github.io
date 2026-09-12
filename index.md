<style>
  /* Move the content slightly further left and give it more room */
  .home-container {
    position: relative;
    left: -40px;
    width: calc(100% + 80px);
  }

  /* CV + LinkedIn — clean text like Andre Gray */
  .top-links {
    font-size: 16px;
    margin: 0 0 25px 0;
  }

  .top-links a {
    color: #2a6496;
    text-decoration: none;
    margin-right: 28px;
  }

  .top-links a:hover {
    text-decoration: underline;
  }

  /* Photo + profile information */
  .profile-container {
    display: flex;
    align-items: flex-start;
    gap: 40px;
    margin-bottom: 55px;
  }

  .profile-photo {
    width: 270px;
    height: 340px;
    object-fit: cover;
    border-radius: 8px;
    flex-shrink: 0;
  }

  .profile-info {
    flex: 1;
    min-width: 0;
    padding-top: 0;
  }

  .profile-info h1 {
    margin: 0 0 12px 0;
    font-size: 38px;
  }

  .degree {
    font-size: 20px;
    color: #555;
    margin: 0 0 25px 0;
    white-space: nowrap;
  }

  .description {
    font-size: 18px;
    line-height: 1.65;
    color: #555;
    max-width: 700px;
    margin: 0;
  }

  /* Keep Projects clean and separate */
  .projects-section {
    border-top: 1px dashed #ccc;
    padding-top: 25px;
  }

  @media (max-width: 850px) {
    .home-container {
      left: 0;
      width: 100%;
    }

    .profile-container {
      flex-direction: column;
    }

    .profile-photo {
      width: 270px;
      height: 340px;
    }

    .degree {
      white-space: normal;
    }

    .description {
      max-width: 100%;
    }
  }
</style>


<div class="home-container">

  <!-- CV + LinkedIn -->
  <div class="top-links">
    <a href="/Jose_Nunes.pdf">CV</a>
    <a href="https://linkedin.com/in/josepnunes/" target="_blank">LinkedIn</a>
  </div>


  <!-- Profile -->
  <div class="profile-container">

    <img src="/profile.png" class="profile-photo">

    <div class="profile-info">

      <h1>José Nunes</h1>

      <p class="degree">
        BSc in Economics, Nova School of Business and Economics
      </p>

      <p class="description">
        I am an intern at the Portuguese Energy Sector Regulator (ERSE)
        with interests in development economics, public policy, industrial
        organization, and economic regulation.
      </p>

    </div>

  </div>


  <div class="projects-section">

# Projects

### ["The Impact of ICT Regulations on the Achievement Gap in Mathematics: A Cross-Sectional Analysis"](/PISA_ICT_Math.pdf)
<details markdown="1">
<summary>Abstract</summary>

This study examines whether stricter school-level ICT regulation can reduce socioeconomic disparities in Mathematics performance. Using OECD PISA 2022 data from 81,850 students across ten developed economies, we estimate a series of Weighted Least Squares models incorporating socioeconomic, behavioural, demographic, institutional, and country-level controls. The results indicate that stronger ICT regulation is positively associated with Mathematics scores and has an additional positive association for students from disadvantaged socioeconomic backgrounds, suggesting that school-level digital policies may contribute to reducing achievement gaps.

My contribution: responsible for the results and R code (including all graphs). Grade: 19/20
</details>

### ["Socioeconomic and Structural Factors in Innovation Gaps: Eastern vs. Western European Union"](/EU_Innovation_Gaps.pdf)
<details markdown="1">
<summary>Abstract</summary>

This study investigates the extent to which socioeconomic and structural factors explain differences in innovation performance between Eastern and Western EU member states. Using patent applications to the European Patent Office (EPO) in 2017 as a proxy for innovation output, alongside Eurostat data on population, R&D expenditure, education levels, and unemployment, the analysis applies a series of OLS regression models incorporating an East-West regional indicator. The results show that while these socioeconomic and structural factors help explain patenting activity, a substantial and statistically significant gap between Eastern and Western EU countries persists even after controlling for them, suggesting that structural or institutional differences not captured by these variables continue to drive the divide in innovation output.

My contribution: responsible for the results, robustness checks, and R code (including all graphs). Grade: 18/20
</details>

### ["Tuition Fee Reform Policy Recommendation"](/Tuition_Fee_Reform.pdf)
<details markdown="1">
<summary>Abstract</summary>

Evaluating Germany's tuition reforms as a natural experiment, this paper examines the economic and distributional impacts of higher university fees. The evidence reveals significant drops in enrollment and shifts in application behavior. Applying public economic theory, including efficiency, price elasticity, and equity, the study demonstrates that higher fees yield substantial social costs, making a strong case for public funding to preserve access and capture broader human capital externalities.

Grade: 18/20
</details>

  </div>

</div>

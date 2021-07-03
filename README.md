<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <!-- <link rel="stylesheet" href="assests/css/style.css" /> -->
  </head>
  <body>
    <div
      class="container"
      style="
        background: url('/assests/img/triangle.png');
        background-repeat: no-repeat;
        background-size: 100% 100%;
        padding: 0 0 20px 0;
      "
    >
      <img
        src="assests/img/kaguya.webp"
        alt="Name explain"
        id="profile-img"
        style="
          width: 100%;
          display: block;
          margin-left: auto;
          margin-right: auto;
        "
      />
      <div
        class="status-card-container"
        style="
          margin-top: 20px;
          padding-left: 20px;
          padding-right: 20px;
          display: flex;
          flex-direction: row;
          justify-content: space-evenly;
        "
      >
        <img
          id="git-stat"
          class="status-card"
          src="https://github-readme-stats.vercel.app/api?username=tarzanchemgio&count_private=true&show_icons=true&theme=dracula&border_radius=8&include_all_commits=true&custom_title=Kafka Wanna Fly"
          alt="Profile stats"
          style="height: 15vw"
        />
        <img
          id="git-language"
          class="status-card"
          src="https://github-readme-stats.vercel.app/api/top-langs/?username=tarzanchemgio&layout=compact&theme=dracula"
          alt="Top language"
          style="height: 15vw"
        />
      </div>
    </div>
  </body>
</html>

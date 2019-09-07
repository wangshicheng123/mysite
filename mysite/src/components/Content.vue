<template>
  <div class="container">
    <div class="row about">
      <div class="col-md-12">
        <h2>About Me</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-md-4 infor">
        <ul>
          <li>
            <span class="title">Full Name:</span>
            <span class="descrip">Louie Jie Mahusay</span>
          </li>
          <li>
            <span class="title">Phone:</span>
            <span class="descrip">+ 1235 2355 98</span>
          </li>
          <li>
            <span class="title">Email:</span>
            <span class="descrip">info@yoursite.com</span>
          </li>
          <li>
            <span class="title">Website</span>
            <span class="descrip">www.yoursite.com</span>
          </li>
          <li>
            <span class="title">Address:</span>
            <span class="descrip">198 West 21th Street, Suite 721 New York NY 10016</span>
          </li>
        </ul>
      </div>
      <div class="col-md-8 intro">
        <h2 class="title">Hello There!</h2>
        <p>There live the blind texts far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in bookmarksgrove there live the blind texts far from the countries.</p>
        <p>Far far away, behind the word mountains, Quos quia provident consequuntur culpa facere ratione maxime commodi voluptates id repellat velit eaque aspernatur expedita. Possimus itaque adipisci there live the blind texts from the countries Vokalia and Consonantia, there live the blind texts. Quos quia provident consequuntur culpa facere ratione maxime commodi voluptates id repellat velit eaque aspernatur expedita. Possimus itaque adipisci.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container {
  padding: 112px 0px;
  margin: 0px 70px;
}
.about {
  padding-bottom: 80px;
}
.about h2 {
  text-align: center;
  font-weight: 400;
  font-size: 40px;
  letter-spacing: 3px;
}
.infor {
  padding: 0px 12px;
}
.infor ul {
  list-style-type: none;
  margin: 0px;
  padding: 0px 35px;
  font-family: "Space Mono", Arial, serif;
}
.infor ul li {
  padding-bottom: 10px;
  font-weight: 400;
  font-size: 18px;
  line-height: 1.7;
}
.infor li .title {
  color: #000;
  font-weight: bold;
  width: 40%;
  float: left;
}
.infor li .descrip {
  width: 60%;
  display: inline-block;
  color: rgba(0, 0, 0, 0.5);
  line-height: 1.7;
}
.intro{
  padding-left: 50px;
}
.intro .title {
  margin-bottom: 20px;
  font-weight: 400;
}
.intro p {
  margin-bottom: 30px;
  font-weight: 450;
  font-size: 17px;
  line-height: 1.7;
  color: #4d4d4d;
}
</style>
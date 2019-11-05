---
title: Takım
date: 2019-09-30 16:00:28
tags:
---


<style>
.at-section__title {
  margin: 0 0 70px;
  color: #000;
  font-family: 'Roboto', sans-serif;
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 2.625rem;
  text-align: center;
}
.at-grid {
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  background: #FFF;
  border: 1px solid #E2E9ED;
}
.at-grid[data-column="1"] .at-column {
  width: 100%;
  max-width: 100%;
  min-width: 100%;
  flex-basis: 100%;
}
.at-grid[data-column="2"] .at-column {
  width: 50%;
  max-width: 50%;
  min-width: 50%;
  flex-basis: 50%;
}
.at-grid[data-column="3"] .at-column {
  width: 33.3333333333%;
  max-width: 33.3333333333%;
  min-width: 33.3333333333%;
  flex-basis: 33.3333333333%;
}
.at-column {
  z-index: 0;
  position: relative;
  background: #FFF;
  box-shadow: 0 0 0 1px #E2E9ED;
  padding: 10px;
  box-sizing: border-box;
  transition: box-shadow 0.2s ease, transform 0.2s ease, z-index 0s 0.2s ease;
}
.at-column:before {
  content: "";
  display: block;
  padding-top: 100%;
}
.at-column:hover {
  z-index: 1;
  box-shadow: 0 8px 50px rgba(0, 0, 0, 0.2);
  transform: scale(1.05);
  transition: box-shadow 0.2s ease, transform 0.2s ease, z-index 0s 0s ease;
}
.at-column:hover .at-social {
  margin: 16px 0 0;
  opacity: 1;
}
@media (max-width: 800px) {
  .at-column {
    width: 50% !important;
    max-width: 50% !important;
    min-width: 50% !important;
    flex-basis: 50% !important;
  }
}
@media (max-width: 600px) {
  .at-column {
    width: 100% !important;
    max-width: 100% !important;
    min-width: 100% !important;
    flex-basis: 100% !important;
  }
}
.at-user {
  position: absolute;
  top: 50%;
  left: 0;
  width: 100%;
  transform: translate(0, -50%);
  text-align: center;
}
.at-user__avatar {
  width: 98px;
  height: 98px;
  border-radius: 100%;
  margin: 0 auto 20px;
  overflow: hidden;
}
.at-user__avatar img {
  display: block;
  width: 100%;
  max-width: 100%;
  margin:0;
}
.at-user__name {
  color: #313435;
  font-family: 'Roboto', sans-serif;
  font-size: 1.5rem;
  font-weight: 500;
  line-height: 2.625rem;
}
.at-user__title {
  color: #6F808A;
  font-family: 'Roboto', sans-serif;
  font-size: 0.875rem;
  line-height: 2.375rem;
}

body {
  background: #FFF;
  font-family: 'Roboto', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.container {
  width: 100%;
  margin: 100px auto;
  padding: 0;
  box-sizing: border-box;
  transform-origin: top center;
}

</style>


<div class="container">
  <div class="at-grid" data-column="3">
    <a class="at-column" href="/tags/atagulalan">
      <div class="at-user">
        <div class="at-user__avatar"><img src="https://avatars1.githubusercontent.com/u/8681330?s=460&amp;v=4"/></div>
        <div class="at-user__name">Ata Gülalan</div>
        <div class="at-user__title">atagulalan</div>
      </div>
    </a>
    <a class="at-column" href="/tags/oguzturker8">
      <div class="at-user">
        <div class="at-user__avatar"><img src="https://avatars2.githubusercontent.com/u/33129613?s=460&amp;v=4"/></div>
        <div class="at-user__name">Oğuzhan Türker</div>
        <div class="at-user__title">oguzturker8</div>
      </div>
    </a>
    <a class="at-column" href="/tags/fxy0">
      <div class="at-user">
        <div class="at-user__avatar"><img src="https://avatars3.githubusercontent.com/u/32413273?s=460&amp;v=4"/></div>
        <div class="at-user__name">Serdar Tunalı</div>
        <div class="at-user__title">stunali</div>
      </div>
    </a>
  </div>
</div>

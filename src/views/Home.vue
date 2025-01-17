<template>
  <div class="container">
    <div id="name-container">
      <img id="avatar" src="./../assets/images/av.png" alt="avatar" />
      <h1>Yousri Yan</h1>
    </div>
    <div class="title-desc-container">
      <a id="sre" href="https://sre.google" target="_blank" rel="noopener noreferrer">
      <img class="title-font" src="./../assets/images/sre.png" />SRE
      <span>/</span>
      <a id="devops" href="https://aws.amazon.com/devops/what-is-devops/" target="_blank" rel="noopener noreferrer">
      <img class="title-font" src="./../assets/images/devops.png" />DevOps
      <span>/</span>
      <a id="blog" href="https://blog.yousri.org" target="_blank" rel="noopener noreferrer">
      <img class="title-font" src="./../assets/images/zeit.svg" />Blogger</a
      >
    </div>
    <div class="article">
      <h2>WHO AM I</h2>
      <p>
        My name is <i>Yousri Yan</i>.<br>
	Job as <i>SRE</i> and <i>DevOps</i>, part-time as <i>DBA</i>.<br>
	Come from a small village of Xiamen, and prefer like country life to city life.<br>
	You can follow me on <a href="https://twitter.com/yousri" target="_blank" rel="noopener noreferrer">Twitter</a> and <a href="https://weibo.com/yousri" target="_blank" rel="noopener noreferrer">Weibo</a>.<br>
	About life photo on <a href="https://instagram.com/imyousri" target="_blank" rel="noopener noreferrer">Instagram</a>.
      </p>

      <h2>Interests</h2>
      <ul>
        <li>Enjoy <i>Photography</i>,<i>Cycling</i> and <i>Traveling</i>.</li>
        <li>Pursuing <i>simple</i>,<i>plain</i> Life and the most <i>simple</i> Dreams.</li>
      </ul>

      <h2>Devices</h2>
      <ul>
        <li>⚫ Mac mini 2 / MacBook Pro (16-inch, 2019)</li>
        <li>🔵 iPhone Pro 15 / iPhone 12 mini</li>
        <li>🔵 iPad mini 4</li>
        <li>⚫ AirPods 3</li>
      </ul>

      <h2>Contacts</h2>
      <ul>
        <li>
          <b>IM：</b>
          <a href="https://t.me/imyousri" target="_blank">Telegram</a>
        </li>
        <li>
          <b>Email：</b>
          <a href="mailto:qingxianyan@gmail.com">qingxianyan#gmail.com</a>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="css" scoped>
#name-container {
  display: flex;
  flex-direction: row;
  justify-content: flex-start;
  align-items: center;
}

#avatar {
  width: 42px;
  height: 42px;
  border-radius: 50%;
  margin-right: 12px;
}

#copyright:hover {
  border: none;
}

.title-font {
  width: 16px;
  height: 16px;
  margin-right: 4px;
}

.title-desc-container {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  margin: 8px 0;
}

.title-desc-container a {
  display: flex;
  align-items: center;
}

.title-desc-container span {
  margin: 0px 4px;
}

.title-desc-container #github {
  color: #24292e;
}

.title-desc-container #sspai {
  color: #ca2c2a;
}

.title-desc-container #blog {
  color: #0070f3;
}
</style>

<script setup>
</script>

<template>
  <div class="dashboard">
    <!-- topmenu -->
    <div class="nav-top">
      <div class="nav-top-menu">
        <ul>
          <li>
            notification icon
          </li>
          <li>
            calendar icon
          </li>
          <li>
            dark light mode button
          </li>
          <li>
            <div class="welcome-text">
              <div class="avatar"></div>
              <p>Bacon Su Welcome!</p>
            </div>
          </li>
        </ul>
      </div>
    </div>
    <!-- sidebar -->
    <div class="main-layout">
      <div class="sidebar">
        <div class="sidebar-container">
          <div class="sidebar-menu">
            <ul class="sidebar-menu-item">
              <li class="item btn">
                <i class="icon fa fa-home"></i>
                <span class="text">+ 新增事項</span>
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">Dashboard</span>
                </a>
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">我的假單</span>
                </a>
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">簽核</span>
                </a>
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">組織設定</span>
                </a>
              </li>
            </ul>
            <ul class="sidebar-menu-item">
              <li>
                Support
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">個人化設定</span>
                </a>
              </li>
              <li class="item">
                <a href="">
                  <i class="icon fa fa-home"></i>
                  <span class="text">登出</span>
                </a>
              </li>
            </ul>
          </div>
          <div class="sidebar-menu-bottom">

          </div>
        </div>
      </div>
      <!-- main -->
      <main>
        <!-- card -->
        <section class="card">
          <div class="card-container">
            <div class="card-header">
              <p>假單</p>
            </div>
            <div class="card-body">
              <div class="card-body-left">
                <ul>
                  <li>
                    <p>簽合中 1</p>
                  </li>
                  <li>
                    <p>已核准 0</p>
                  </li>
                  <li>
                    <p>已退回 0</p>
                  </li>
                </ul>
              </div>
              <div class="card-body-right">
                <a href="">MORE</a>
              </div>
            </div>
          </div>
          <div class="card-container">
            <div class="card-header">
              <p>簽核</p>
            </div>
            <div class="card-body">
              <div class="card-body-left">
                <ul>
                  <li>
                    <p>待簽核 2</p>
                  </li>
                </ul>
              </div>
              <div class="card-body-right">
                <a href="">MORE</a>
              </div>
            </div>
          </div>
          <div class="card-container">
            <div class="card-header">
              <p>打卡</p>
            </div>
            <div class="card-body">
              <ul class="card-body-item">
                <li>
                  <button>
                    <p>上班</p>
                  </button>
                </li>
                <li>
                  <button>
                    <p>下班</p>
                  </button>
                </li>
              </ul>
            </div>
          </div>
        </section>
        <section class="content">
          <div class="content-left">
            <div class="activity">
              <div class="activity-header">
                <p>今日請假人員</p>
              </div>
              <div class="activity-body">
                <div class="left">
                  <div class="avatar"></div>
                </div>
                <div class="center">
                  <div class="info">
                    <p>Tim</p>
                    <p>Tim.wang@gmail.com</p>
                  </div>
                </div>
                <div class="right">
                  <div class="status">
                    <p>假別</p>
                  </div>
                </div>
              </div>
              <div class="activity-body">
                <div class="left">
                  <div class="avatar"></div>
                </div>
                <div class="center">
                  <div class="info">
                    <p>Tim</p>
                    <p>Tim.wang@gmail.com</p>
                  </div>
                </div>
                <div class="right">
                  <div class="status">
                    <p>假別</p>
                  </div>
                </div>
              </div>
              <div class="activity-body">
                <div class="left">
                  <div class="avatar"></div>
                </div>
                <div class="center">
                  <div class="info">
                    <p>Tim</p>
                    <p>Tim.wang@gmail.com</p>
                  </div>
                </div>
                <div class="right">
                  <div class="status">
                    <p>假別</p>
                  </div>
                </div>
              </div>
            </div>
            <div class="activity activity-news">
              <div class="activity-header">
                <p>最新公告</p>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
              <div class="activity-body">
                <div class="row">
                  <p>2023/09/18</p>
                </div>
                <div class="row">
                  <p>標題</p>
                </div>
                <div class="row">
                  <p>主旨：辦公室清潔</p>
                </div>
                <div class="row">
                  <p>發佈單位</p>
                </div>
              </div>
            </div>
          </div>
          <!-- activity -->
          <div class="content-right">
            <div class="activity">
              <div class="activity-header">
                <p>今日行程 2023/09/18</p>
              </div>
              <div class="activity-body">
                <div class="time">
                  <p>09:00</p>
                  <p>10:00</p>
                  <p>11:00</p>
                  <p>12:00</p>
                  <p>13:00</p>
                  <p>14:00</p>
                  <p>15:00</p>
                  <p>16:00</p>
                  <p>17:00</p>
                  <p>18:00</p>
                  <p>19:00</p>
                  <p>20:00</p>
                </div>
                <div class="event">
                  <div class="event-item">
                    <div class="event-item-left"></div>
                    <div class="event-item-right"></div>
                  </div>
                  <div class="event-item" style="height: 100px">
                    <div class="event-item-left"></div>
                    <div class="event-item-right"></div>
                  </div>
                  <div class="event-item">
                    <div class="event-item-left"></div>
                    <div class="event-item-right"></div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </section>
      </main>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.dashboard {
  min-width: 1080px;
  min-height: 100%;
  padding: 10px;
}

.nav-top {
  background-color: var(--gray-10);
  height: 60px;
  padding: 0 40px;
  border-radius: 60px 60px 0 0;

  .nav-top-menu {
    display: flex;
    align-items: center;
    height: 100%;
    width: 100%;
  }

  ul {
    display: inline-flex;
    align-items: center;
    justify-content: flex-end;
    height: 100%;
    width: 100%;

    li {
      margin-left: 20px;
      font-size: var(--font-size-2);
      font-weight: var(--font-weight-5);
      color: var(--gray-6);
    }
  }

  li .welcome-text {
    display: flex;
    align-items: center;
    justify-content: center;

    .avatar {
      height: 38px;
      width: 38px;
      background-color: var(--blue-10);
      border-radius: 100%;
      margin-right: 8px;
    }
  }
}

.main-layout {
  display: flex;
}

.sidebar-container {
  background-color: var(--gray-10);
  height: calc(100vh - 80px);
  width: 240px;
  top: 60px;
  left: 0;
  padding: 20px;
  border-radius: 0 0 0 60px;
}

.sidebar-menu {
  display: flex;
  flex-direction: column;
  margin-left: 40px;

  ul.sidebar-menu-item {
    &:nth-child(2) {
      margin-top: 60px;
    }

    li {
      text-align: center;
      height: 32px;
      width: 140px;
    }

    li:not(:first-of-type) {
      background-color: var(--blue-10);
      border-radius: 8px;

      line-height: 32px;
      margin-bottom: 12px;
      text-align: center;
    }

    li,
    a {
      color: var(--gray-4);
    }
  }
}

.sidebar-menu-item .btn {
  margin-bottom: 40px;

  span {
    color: var(--indigo-11);
  }
}

main {
  background-color: var(--gray-10);
  padding: 20px;
  width: 100%;
}

section.card {
  display: flex;
  align-items: flex-start;
  flex-wrap: wrap;
}

.card-container {
  display: flex;
  flex-direction: column;
  background-color: var(--gray-3);
  border-radius: 16px;
  box-shadow: var(--shadow-4);
  color: var(--gray-8);
  height: 200px;
  width: calc(100% / 3 - 20px);
  margin: 0 20px 20px 0;

  .card-header {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    height: 40px;
    margin: 12px 0 0 12px;

    p {
      font-size: var(--font-size-5);
      line-height: normal;
      width: 100%;
    }
  }

  .card-body {
    display: flex;
    align-items: center;
    justify-content: space-between;
    height: 160px;

    p {
      font-size: var(--font-size-4);
      line-height: normal;
      padding: 0 12px;
    }
  }
}

.card-body-right {
  display: flex;
  align-self: flex-end;
  margin: 0 12px 24px 0;
  font-size: var(--font-size-2);
}

.card-body-item {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: auto;

  li:nth-child(1) {
    margin-right: 12px;
  }
}

section.content {
  position: relative;
  display: flex;

  .content {
    &-left {
      width: 60%;
    }

    &-right {
      width: 40%;
    }
  }
}

.activity {
  background-color: var(--gray-3);
  border-radius: 16px;
  max-height: calc(100vh - 380px);
  margin-right: 20px;
  overflow-y: scroll;
}

.activity-news {
  margin-top: 20px;
  max-height: calc((100vh - 380px) / 2 - 30px);

  .row {
    width: 25%;
    padding: 8px;
  }
}

.activity-header {
  padding: 12px 12px 12px 12px;

  p {
    color: var(--gray-8);
    font-size: var(--font-size-3);
    font-weight: var(--font-weight-5);
  }
}

.activity-body {
  display: flex;
  padding: 12px 12px 12px 12px;
}

.time {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: flex-start;

  p {
    height: 100px;
  }
}

.event {
  display: flex;
  flex-direction: column;
  justify-content: flex-start;
  width: 100%;

  .event-item {
    background-color: var(--blue-10);
    border-radius: 8px;
    width: 96%;
    height: 40px;
    margin-left: 12px;
    margin-bottom: 100px;
    padding: 4px 4px;

    .event-item-left {
      display: flex;
      align-items: center;
      background-color: var(--blue-4);
      border-radius: 8px;
      width: 48px;
      height: 100%;
    }
  }
}

.left,
.center,
.right {
  display: flex;
  align-items: center;
  margin-left: 1rem;
  padding: 12px;
  width: 200px;
}

.left {
  display: flex;
  align-items: center;
  width: 70px;

  .avatar {
    height: 38px;
    width: 38px;
    background-color: var(--blue-10);
    border-radius: 100%;
  }
}

.center {
  flex-grow: 1;
}

.info {
  display: flex;
  flex-direction: column;
  width: 100%;
}

.status {
  margin-left: auto;
  text-align: right;
}
</style>
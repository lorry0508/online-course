<template>
  <div>
    <div id="navbar" className="navbar navbar-default          ace-save-state">
      <div className="navbar-container ace-save-state" id="navbar-container">
        <button type="button" className="navbar-toggle menu-toggler pull-left" id="menu-toggler" data-target="#sidebar">
          <span className="sr-only">Toggle sidebar</span>

          <span className="icon-bar"></span>

          <span className="icon-bar"></span>

          <span className="icon-bar"></span>
        </button>

        <div className="navbar-header pull-left">
          <a href="index.html" className="navbar-brand">
            <small>
              <i className="fa fa-leaf"></i>
              在线视频课程
            </small>
          </a>
        </div>

        <div className="navbar-buttons navbar-header pull-right" role="navigation">
          <ul className="nav ace-nav">
            <li className="grey dropdown-modal">
              <a data-toggle="dropdown" className="dropdown-toggle" href="#">
                <i className="ace-icon fa fa-tasks"></i>
                <span className="badge badge-grey">4</span>
              </a>

              <ul className="dropdown-menu-right dropdown-navbar dropdown-menu dropdown-caret dropdown-close">
                <li className="dropdown-header">
                  <i className="ace-icon fa fa-check"></i>
                  4 Tasks to complete
                </li>

                <li className="dropdown-content">
                  <ul className="dropdown-menu dropdown-navbar">
                    <li>
                      <a href="#">
                        <div className="clearfix">
                          <span className="pull-left">Software Update</span>
                          <span className="pull-right">65%</span>
                        </div>

                        <div className="progress progress-mini">
                          <div style="width:65%" className="progress-bar"></div>
                        </div>
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <div className="clearfix">
                          <span className="pull-left">Hardware Upgrade</span>
                          <span className="pull-right">35%</span>
                        </div>

                        <div className="progress progress-mini">
                          <div style="width:35%" className="progress-bar progress-bar-danger"></div>
                        </div>
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <div className="clearfix">
                          <span className="pull-left">Unit Testing</span>
                          <span className="pull-right">15%</span>
                        </div>

                        <div className="progress progress-mini">
                          <div style="width:15%" className="progress-bar progress-bar-warning"></div>
                        </div>
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <div className="clearfix">
                          <span className="pull-left">Bug Fixes</span>
                          <span className="pull-right">90%</span>
                        </div>

                        <div className="progress progress-mini progress-striped active">
                          <div style="width:90%" className="progress-bar progress-bar-success"></div>
                        </div>
                      </a>
                    </li>
                  </ul>
                </li>

                <li className="dropdown-footer">
                  <a href="#">
                    See tasks with details
                    <i className="ace-icon fa fa-arrow-right"></i>
                  </a>
                </li>
              </ul>
            </li>

            <li className="purple dropdown-modal">
              <a data-toggle="dropdown" className="dropdown-toggle" href="#">
                <i className="ace-icon fa fa-bell icon-animated-bell"></i>
                <span className="badge badge-important">8</span>
              </a>

              <ul className="dropdown-menu-right dropdown-navbar navbar-pink dropdown-menu dropdown-caret dropdown-close">
                <li className="dropdown-header">
                  <i className="ace-icon fa fa-exclamation-triangle"></i>
                  8 Notifications
                </li>

                <li className="dropdown-content">
                  <ul className="dropdown-menu dropdown-navbar navbar-pink">
                    <li>
                      <a href="#">
                        <div className="clearfix">
													<span className="pull-left">
														<i className="btn btn-xs no-hover btn-pink fa fa-comment"></i>
														New Comments
													</span>
                          <span className="pull-right badge badge-info">+12</span>
                        </div>
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <i className="btn btn-xs btn-primary fa fa-user"></i>
                        Bob just signed up as an editor ...
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <div className="clearfix">
													<span className="pull-left">
														<i className="btn btn-xs no-hover btn-success fa fa-shopping-cart"></i>
														New Orders
													</span>
                          <span className="pull-right badge badge-success">+8</span>
                        </div>
                      </a>
                    </li>

                    <li>
                      <a href="#">
                        <div className="clearfix">
													<span className="pull-left">
														<i className="btn btn-xs no-hover btn-info fa fa-twitter"></i>
														Followers
													</span>
                          <span className="pull-right badge badge-info">+11</span>
                        </div>
                      </a>
                    </li>
                  </ul>
                </li>

                <li className="dropdown-footer">
                  <a href="#">
                    See all notifications
                    <i className="ace-icon fa fa-arrow-right"></i>
                  </a>
                </li>
              </ul>
            </li>

            <li className="green dropdown-modal">
              <a data-toggle="dropdown" className="dropdown-toggle" href="#">
                <i className="ace-icon fa fa-envelope icon-animated-vertical"></i>
                <span className="badge badge-success">5</span>
              </a>

              <ul className="dropdown-menu-right dropdown-navbar dropdown-menu dropdown-caret dropdown-close">
                <li className="dropdown-header">
                  <i className="ace-icon fa fa-envelope-o"></i>
                  5 Messages
                </li>

                <li className="dropdown-content">
                  <ul className="dropdown-menu dropdown-navbar">
                    <li>
                      <a href="#" className="clearfix">
                        <img src="../../public/ace/assets/images/avatars/avatar.png" className="msg-photo"
                             alt="Alex's Avatar"/>
                        <span className="msg-body">
													<span className="msg-title">
														<span className="blue">Alex:</span>
														Ciao sociis natoque penatibus et auctor ...
													</span>

													<span className="msg-time">
														<i className="ace-icon fa fa-clock-o"></i>
														<span>a moment ago</span>
													</span>
												</span>
                      </a>
                    </li>

                    <li>
                      <a href="#" className="clearfix">
                        <img src="../../public/ace/assets/images/avatars/avatar3.png" className="msg-photo"
                             alt="Susan's Avatar"/>
                        <span className="msg-body">
													<span className="msg-title">
														<span className="blue">Susan:</span>
														Vestibulum id ligula porta felis euismod ...
													</span>

													<span className="msg-time">
														<i className="ace-icon fa fa-clock-o"></i>
														<span>20 minutes ago</span>
													</span>
												</span>
                      </a>
                    </li>

                    <li>
                      <a href="#" className="clearfix">
                        <img src="../../public/ace/assets/images/avatars/avatar4.png" className="msg-photo"
                             alt="Bob's Avatar"/>
                        <span className="msg-body">
													<span className="msg-title">
														<span className="blue">Bob:</span>
														Nullam quis risus eget urna mollis ornare ...
													</span>

													<span className="msg-time">
														<i className="ace-icon fa fa-clock-o"></i>
														<span>3:15 pm</span>
													</span>
												</span>
                      </a>
                    </li>

                    <li>
                      <a href="#" className="clearfix">
                        <img src="../../public/ace/assets/images/avatars/avatar2.png" className="msg-photo"
                             alt="Kate's Avatar"/>
                        <span className="msg-body">
													<span className="msg-title">
														<span className="blue">Kate:</span>
														Ciao sociis natoque eget urna mollis ornare ...
													</span>

													<span className="msg-time">
														<i className="ace-icon fa fa-clock-o"></i>
														<span>1:33 pm</span>
													</span>
												</span>
                      </a>
                    </li>

                    <li>
                      <a href="#" className="clearfix">
                        <img src="../../public/ace/assets/images/avatars/avatar5.png" className="msg-photo"
                             alt="Fred's Avatar"/>
                        <span className="msg-body">
													<span className="msg-title">
														<span className="blue">Fred:</span>
														Vestibulum id penatibus et auctor  ...
													</span>

													<span className="msg-time">
														<i className="ace-icon fa fa-clock-o"></i>
														<span>10:09 am</span>
													</span>
												</span>
                      </a>
                    </li>
                  </ul>
                </li>

                <li className="dropdown-footer">
                  <a href="inbox.html">
                    See all messages
                    <i className="ace-icon fa fa-arrow-right"></i>
                  </a>
                </li>
              </ul>
            </li>

            <li className="light-blue dropdown-modal">
              <a data-toggle="dropdown" href="#" className="dropdown-toggle">
                <img className="nav-user-photo" src="../../public/ace/assets/images/avatars/user.jpg"
                     alt="Jason's Photo"/>
                <span className="user-info">
									<small>Welcome,</small>
									Jason
								</span>

                <i className="ace-icon fa fa-caret-down"></i>
              </a>

              <ul className="user-menu dropdown-menu-right dropdown-menu dropdown-yellow dropdown-caret dropdown-close">
                <li>
                  <a href="#">
                    <i className="ace-icon fa fa-cog"></i>
                    Settings
                  </a>
                </li>

                <li>
                  <a href="profile.html">
                    <i className="ace-icon fa fa-user"></i>
                    Profile
                  </a>
                </li>

                <li className="divider"></li>

                <li>
                  <a href="#">
                    <i className="ace-icon fa fa-power-off"></i>
                    Logout
                  </a>
                </li>
              </ul>
            </li>
          </ul>
        </div>
      </div><!-- /.navbar-container -->
    </div>

    <div className="main-container ace-save-state" id="main-container">
      <div id="sidebar" className="sidebar                  responsive                    ace-save-state">

        <div className="sidebar-shortcuts" id="sidebar-shortcuts">
          <div className="sidebar-shortcuts-large" id="sidebar-shortcuts-large">
            <button className="btn btn-success">
              <i className="ace-icon fa fa-signal"></i>
            </button>

            <button className="btn btn-info">
              <i className="ace-icon fa fa-pencil"></i>
            </button>

            <button className="btn btn-warning">
              <i className="ace-icon fa fa-users"></i>
            </button>

            <button className="btn btn-danger">
              <i className="ace-icon fa fa-cogs"></i>
            </button>
          </div>

          <div className="sidebar-shortcuts-mini" id="sidebar-shortcuts-mini">
            <span className="btn btn-success"></span>

            <span className="btn btn-info"></span>

            <span className="btn btn-warning"></span>

            <span className="btn btn-danger"></span>
          </div>
        </div><!-- /.sidebar-shortcuts -->

        <ul className="nav nav-list">
          <li className="" id="welcome-sidebar">
            <router-link to="/welcome">
              <i className="menu-icon fa fa-tachometer"></i>
              <span className="menu-text"> 欢迎 </span>
            </router-link>

            <b className="arrow"></b>
          </li>

          <li className="">
            <a href="#" className="dropdown-toggle">
              <i className="menu-icon fa fa-list"></i>
              <span className="menu-text"> 系统管理 </span>

              <b className="arrow fa fa-angle-down"></b>
            </a>

            <b className="arrow"></b>

            <ul className="submenu">
              <li className="">
                <a href="tables.html">
                  <i className="menu-icon fa fa-caret-right"></i>
                  用户管理
                </a>

                <b className="arrow"></b>
              </li>

              <li className="">
                <a href="jqgrid.html">
                  <i className="menu-icon fa fa-caret-right"></i>
                  权限管理
                </a>

                <b className="arrow"></b>
              </li>
            </ul>
          </li>

          <li className="active open">
            <a href="#" className="dropdown-toggle">
              <i className="menu-icon fa fa-list"></i>
              <span className="menu-text"> 业务管理 </span>

              <b className="arrow fa fa-angle-down"></b>
            </a>

            <b className="arrow"></b>

            <ul className="submenu">
              <li className="active" id="business-chapter-sidebar">
                <router-link to="/business/chapter">
                  <i className="menu-icon fa fa-caret-right"></i>
                  大章管理
                </router-link>

                <b className="arrow"></b>
              </li>

            </ul>
          </li>

        </ul><!-- /.nav-list -->

        <div className="sidebar-toggle sidebar-collapse" id="sidebar-collapse">
          <i id="sidebar-toggle-icon" className="ace-icon fa fa-angle-double-left ace-save-state"
             data-icon1="ace-icon fa fa-angle-double-left" data-icon2="ace-icon fa fa-angle-double-right"></i>
        </div>
      </div>

      <div className="main-content">
        <div className="main-content-inner">
          <div className="page-content">
            <div className="row">
              <div className="col-xs-12">
                <!-- PAGE CONTENT BEGINS -->
                <router-view/>
                <!-- PAGE CONTENT ENDS -->
              </div><!-- /.col -->
            </div><!-- /.row -->
          </div><!-- /.page-content -->
        </div>
      </div><!-- /.main-content -->

      <div className="footer">
        <div className="footer-inner">
          <div className="footer-content">
						<span className="bigger-120">
							<span className="blue bolder">甲蛙</span>
							在线视频课程 &copy; 2099-2099
						</span>

            &nbsp; &nbsp;
            <span className="action-buttons">
							<a href="#">
								<i className="ace-icon fa fa-twitter-square light-blue bigger-150"></i>
							</a>

							<a href="#">
								<i className="ace-icon fa fa-facebook-square text-primary bigger-150"></i>
							</a>

							<a href="#">
								<i className="ace-icon fa fa-rss-square orange bigger-150"></i>
							</a>
						</span>
          </div>
        </div>
      </div>

      <a href="#" id="btn-scroll-up" className="btn-scroll-up btn btn-sm btn-inverse">
        <i className="ace-icon fa fa-angle-double-up icon-only bigger-110"></i>
      </a>
    </div><!-- /.main-container -->
  </div>
</template>

<script>
export default {
  name: "admin",
  mounted: function () {
    let _this = this;
    $("body").removeClass("login-layout light-login");
    $("body").attr("class", "no-skin");
    // console.log("admin");
    // sidebar激活样式方法二
    _this.activeSidebar(_this.$route.name.replace("/", "-") + "-sidebar");
  },
  watch: {
    $route: {
      handler: function (val, oldVal) {
        // sidebar激活样式方法二
        console.log("---->页面跳转：", val, oldVal);
        let _this = this;
        _this.$nextTick(function () {  //页面加载完成后执行
          _this.activeSidebar(_this.$route.name.replace("/", "-") + "-sidebar");
        })
      }
    }
  },
  methods: {
    login() {
      this.$router.push("/admin")
    },

    /**
     * 菜单激活样式，id是当前点击的菜单的id
     * @param id
     */
    activeSidebar: function (id) {
      // 兄弟菜单去掉active样式，自身增加active样式
      $("#" + id).siblings().removeClass("active");
      $("#" + id).siblings().find("li").removeClass("active");
      $("#" + id).addClass("active");

      // 如果有父菜单，父菜单的兄弟菜单去掉open active，父菜单增加open active
      let parentLi = $("#" + id).parents("li");
      if (parentLi) {
        parentLi.siblings().removeClass("open active");
        parentLi.addClass("open active");
      }
    }
  }
}
</script>
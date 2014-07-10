andaily-developer
=================

A Scrum application that from <a href="http://andaily.com">andaily.com</a>

<hr/>



andaily-developer, 源自<a href="http://a.andaily.com">andaily</a>开发过程中使用的scrum工具.

<h5>当前版本: 0.1, <a href="http://git.oschina.net/mkk/andaily-developer/attach_files/download?i=2818&u=http%3A%2F%2Ffiles.git.oschina.net%2Fgroup1%2FM00%2F00%2F1D%2FcHwGbFOhQVqACV7hASJfLYuZJTk455.zip%3Ftoken%3D14e89e7b22db28658502b2ffc2453f2c%26ts%3D1403082206%26filename%3Dandaily-developer_0.1.zip"> 下载</a></h5>

<p>
      <h4>运行环境</h4>
      <ol>
             <li>JDK 1.7 +</li>
             <li>MySql 5.5 +</li>
             <li>Tomcat 7 +</li>
      </ol>
</p>

<p>
      <h4>角色定义</h4>
      在系统中定义了4种角色: Super Man, Product Owner, Scrum Master 与 Scrum Member, 介绍如下
      <ol>
             <li>Super Man(类似系统管理员), 在系统中管理用户(Developer), 团队(Team), 项目(Project) 与系统设置(尚未实现), 系统在安装时会初始化一个Super Man 用户信息.
                不参与Scrum的流程, 只定义基础数据.
             </li>
             <li>Product Owner(产品负责人), 管理项目(Project), Backlog与Sprint, 监控Sprint的执行情况, 保证Sprint达到预期目标</li>
             <li>Scrum Master(团队负责人), 可管理Backlog与Sprint, task等, 负责团队的日常监控与管理, 同时也参与任务的执行</li>
             <li>Scrum Member(团队成员), 主要是执行Sprint的具体任务, 保证每一个任务按照完成</li>
      </ol>
</p>

<hr/>
<h4>程序主要功能截图与说明</h4>
<ol>
    <li>
        Sprint 任务列表, 包括任何的创建, 分配, 时间估算, 燃尽图, 以及任何的完成, 移动, 删除, 重置等等, 开发时使用频率极高.
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-sprint_task.jpg" alt="sprint_tasks" style="max-width:800px; "/>
    </li>
    <li>
        Sprint 会议记录, 记录Sprint执行过程中的各种会议(Daily standing, Sprint planning, Sprint review, Retrospective)内容.
         <br/>
        <img src="http://andaily.qiniudn.com/0.1-sprint_meeting.jpg" alt="sprint_meetings" style="max-width:800px; "/>
    </li>
    <li>
        Sprint 列表, 展示项目的所有Sprint信息, 整体进度等信息
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-sprints.jpg" alt="sprints" style="max-width:600px; "/>
    </li>
    <li>
        Backlog 列表,  管理项目的backlog, 主要由 Product Owner 操作 <br/>
        <img src="http://andaily.qiniudn.com/0.1-backlogs.jpg" alt="backlogs" style="max-width:600px; "/>
    </li>
    <li>
        Sprint 时间报表, 实时反映sprint的时间信息与统计数据.
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-time_report.jpg" alt="sprint_form" style="max-width:800px; "/>
    </li>
    <li>
       Sprint 燃尽图
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-burn_down.jpg" alt="ad"/>
    </li>
</ol>

<hr/>

<h4>用户, 团队与项目 部分</h4>

<ol>
    <li>
       用户管理, 每个用户必须选择四种角色中的一种.
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-users.jpg" alt="ad"/>
    </li>
    <li>
       团队管理, 每个团队至少一名Scrum master与一名Scrum member, 团队必须关联一个或多个项目
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-teams.jpg" alt="ad"/>
    </li>
    <li>
       项目管理, 由Super man与Product Owner维护, 项目必须关联一个或多个Product Owner, 并设定项目结束日期.
        <br/>
        <img src="http://andaily.qiniudn.com/0.1-projects.jpg" alt="ad"/>
    </li>

</ol>




<hr/>
<p>
    欢迎关注 Andaily 项目, GIT访问地址: <a href="http://git.oschina.net/mkk/andaily">http://git.oschina.net/mkk/andaily</a>
    <br/>
    Andaily 在线访问地址: <a href="http://a.andaily.com" target="_blank">http://a.andaily.com</a>
</p>

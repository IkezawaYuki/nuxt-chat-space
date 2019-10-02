<template>
    <div id="sideBar">
    <div class="side_header">
        <div class="user">
            <p class="user_name">
                test
            </p>
            <ul class="user_menu">
                <li class="user_menu__list">

                </li>
                <li class="user_menu__list">

                </li>
            </ul>
        </div>
    </div>

    <div class="titles">
        <div class="titles__block titles__block__group_name">
            group_name
        </div>
        <div class="titles__block titles__block__group_name">
            saishin no message
        </div>
    </div>
    </div>
</template>

<script>
export default {
    
}
</script>


<style>
#sideBar {
  color: #FFFFFF;
  width: 300px;
  background-color: #253141;
  height: 100%;
  float: left;
}
#sideBar .user_info {
  line-height: 100px;
  height: 100px;
}
#sideBar .user_info p {
  float: left;
  font-weight: bold;
  padding-left: 20px;
}
#sideBar .user_info .user_menu {
  float: right;
  padding-right: 20px;
}
#sideBar .user_info .user_menu__list {
  display: inline;
}
#sideBar .titles {
  width: 100%;
  height: calc(100% - 100px);
  color: #FFFFFF;
  background-color: #2F3e51;
  overflow: scroll;
}
#sideBar .titles__block {
  color: #FFFFFF;
  text-decoration: none;
  display: block;
  padding-left: 20px;
  padding-right: 20px;
}
#sideBar .titles__block__group_name {
  padding-top: 20px;
  font-size: 15px;
  font-weight: bold;
  height: 50px;
}
#sideBar .titles__block__latest_post {
  font-size: 11px;
  padding-top: 5px;
  height: 50px;
}
</style>
<template>
    <div class="depat">
      <div class="top">
        <div class="topdiyi">
      <h2>考勤管理</h2>
      </div>
      <div class="topdier">
      <span class="xiaotubiao1 iconfont icon-shouye"></span>
      <span class="shouye">首页</span>
       <span class="xiaotubiao1 iconfont icon-dayuhao"></span>
      <span class="bumen">考勤管理</span>
      </div>
      </div>
      <div class="xinzeng" style="border-top:3px solid #d2d6de;background:#ffffff;box-shadow:2px 2px 2px 2px #e6eaef">
       <ul>
         <li class="xinzengjpg">
           <img src="@/assets/img/xinzeng.jpg"/>

           <input class="chazhao" type="text" placeholder="查找..." style="width:117px;height:30px;border:1px solid #dedfe0;margin-left:878px;" />

             <span class="xiaotubiao1 iconfont icon-fangdajing" style="display:inline-block;border:1px solid #dedfe0;width:31px;height:30px;margin-left: -6px;"></span>

         </li>
       </ul>

      <div class="diyi" style="background:#ffffff;">
       <tr class="diyigetr">
         <td style="width:45px;height:40px;font-weight:600;">ID</td>
         <td style="width:90px;height:40px;font-weight:600;">类型</td>
         <td style="width:318px;height:40px;font-weight:600;">时间</td>
         <td style="width:318px;height:40px;font-weight:600;">IP</td>
         <td style="width:318px;height:40px;font-weight:600;">备注</td>
         <td style="width:369px;height:40px;font-weight:600;">状态</td>
         <td style="width:369px;height:40px;font-weight:600;">操作</td>
       </tr>
       <tr style="height:50px;">
          <td>2</td>
          <td>下班</td>
          <td>2015/10/6  23：10：37</td>
          <td>127.0.0.1</td>
          <td></td>
          <td>
              <img src="@/assets/img/zhengchang.jpg"/>
          </td>
          <td>
           <router-link to="./Magicmodify"><img src="@/assets/img/xiugai.jpg" alt=""></router-link>
           <img src="@/assets/img/shanchu.jpg" alt="">

          </td>

       </tr>
        <tr>
          <td>1</td>
          <td>上班</td>
          <td>2015/10/6  23：10：37</td>
          <td>127.0.0.1</td>
          <td>路上塞车，故晚到</td>
          <td>
              <img src="@/assets/img/chidao.jpg"/>
          </td>
          <td>
           <img src="@/assets/img/xiugai.jpg" alt="">
           <img src="@/assets/img/shanchu.jpg" alt="">
          </td>
       </tr>
           </div>
      </div>
    </div>

</template>


<script>
export default {
  name: 'MagicCheck',
  data () {
    return {

    }
  }
}
</script>
<style scoped>

body{
  background: #ecf0f5;
}

.depat{
  /* width:100%; */
  flex:1;
  height:58px;
  background: #ecf0f5;


}
.depat .top{
  display:flex;
  justify-content: space-between;
}
.topdier{
  margin-right:215px;
}
.depat h2{
  display:inline-block;
  height:40px;
  font-size: 24px;
  color:#33334c;
  line-height: 15px;
  text-indent: 14px;
  margin-top:20px;
}

.depat .icon-shouye{
font-size: 10px;

line-height: 65px;
    height: 59px;

}

.xinzengjpg img{
  margin-left:11px;
}
.depat .shouye{
  font-size: 10px;
  color:#444444;
  line-height: 65px;
    height: 59px;
}

.depat .icon-dayuhao{
  margin-left:10px;
  color:#cccccc;
line-height: 65px;
    height: 59px;
}

.depat .bumen{
  color:#777777;
  font-size:12px ;
  line-height: 65px;
      height: 59px;
}

.xinzeng{
  width:1107px;
  height:211px;
}
.icon-fangdajing{
 text-align: center;
 line-height: 27px;

}
.diyi{
  margin-left:10px;
}

@media screen and (max-width:700px){
  .top{
    flex-direction: column;

  }
  .topdier{


     color: #948688;
     margin-top:-10px;




  }
  .icon-shouye{
    line-height: 27px;
    display:inline-block;
  }
}


</style>

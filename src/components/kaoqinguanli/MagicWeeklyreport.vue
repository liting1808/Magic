<template>
    <div class="depat">
      <div class="top">
        <div class="topdiyi">
      <h2>考勤周报表</h2>
      </div>
      <div class="topdier">
      <span class="xiaotubiao1 iconfont icon-shouye"></span>
      <span class="shouye">首页</span>
       <span class="xiaotubiao1 iconfont icon-dayuhao"></span>
      <span class="bumen">考勤周报表</span>
      </div>
      </div>

      <div class="xinzeng" style="border-top:3px solid #d2d6de;background:#ffffff;box-shadow:2px 2px 2px 2px #e6eaef">
       <ul>
         <li class="xinzengjpg">
           <img src="@/assets/img/dayin.jpg"/>
           <img src="@/assets/img/shangyizhou.jpg"/>
           <img src="@/assets/img/xiayizhou.jpg"/>
           <span>2019-03-11至2019-03-17</span>


           <input class="chazhao" type="text" placeholder="查找..." style="width:117px;height:30px;border:1px solid #dedfe0;margin-left:878px;" />

             <span class="xiaotubiao1 iconfont icon-fangdajing" style="display:inline-block;border:1px solid #dedfe0;width:31px;height:30px;margin-left: -6px;"></span>

         </li>
       </ul>

      <div class="diyi" style="background:#ffffff;">
       <tr class="diyigetr">
         <td style="width:90px;height:20px;font-weight:600;">部门</td>
         <td style="width:90px;height:20px;font-weight:600;">成员</td>
         <td style="width:90px;height:20px;font-weight:600;">星期一</td>
         <td style="width:90px;height:20px;font-weight:600;">星期二</td>
         <td style="width:90px;height:20px;font-weight:600;">星期三</td>
         <td style="width:90px;height:20px;font-weight:600;">星期四</td>
         <td style="width:90px;height:20px;font-weight:600;">星期五</td>
         <td style="width:90px;height:20px;font-weight:600;">星期六</td>
         <td style="width:90px;height:20px;font-weight:600;">星期天</td>
       </tr>
       <tr>
          <td>总公司</td>
          <td>李四</td>
          <td></td>
          <td></td>
          <td></td>
          <td>
          </td>
       </tr>
        <tr>
          <td>总公司</td>
          <td>李四</td>
          <td></td>
          <td></td>
          <td></td>
          <td>
          </td>
       </tr>
        <tr>
          <td>总公司</td>
          <td>李四</td>
          <td></td>
          <td></td>
          <td></td>
          <td>
          </td>
       </tr>
           </div>
      </div>
    </div>
</template>


<script>
export default {
  name: 'MagicDepat',
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
  height:58px;
  flex:1;
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

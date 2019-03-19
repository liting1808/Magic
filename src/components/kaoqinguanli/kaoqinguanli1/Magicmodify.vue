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

      <div class="xinzeng" style="border-top:3px solid #d2d6de;background:#ffffff;box-shadow:2px 2px 2px 2px #e6eaef;margin-left:18px;">
       <ul>
         <li class="xinzengjpg">
             <router-link to="MagicCheck">
           <img src="@/img/fanhui.jpg"/>
           </router-link>
       
        
           <input class="chazhao" type="text" placeholder="查找..." style="width:117px;height:30px;border:1px solid #dedfe0;margin-left:878px;" />
           
             <span class="xiaotubiao1 iconfont icon-fangdajing" style="display:inline-block;border:1px solid #dedfe0;width:31px;height:30px;margin-left: -6px;"></span>
         
         </li>
       </ul>
     
            <ul>
                <li style="display:flex;margin-left:10px;">
                    <span style="display:block;width:529px;height:35px;text-weight:600;">类型</span>
                    <span style="display:block;width:529px;height:35px;text-weight:600;margin-left:28px;">备注</span>

                </li>
                 <li style="display:flex;margin-left:10px;">
                   <select id="xiala" style="display:block;width:529px;height:35px;text-weight:600;cursor:not-allowed;background:#eeeeee" name="">
                       <option value="">下班</option>

                   </select>
                 <input  type="text"  style="width:529px;height:35px;margin-left:30px;border:1px solid #d2d6de"/>

                 </li>

                <li style="margin-top:37px;margin-left:10px;">
                   <input type="submit" value="保存" style="width:54px;height:34px;background:#3c8dbc;color:#ffffff;border-radius:4px;"/>
                   <input type="submit" value="取消" style="width:54px;height:34px;background:#f4f4f4;border-radius:4px;border:1px solid #dddddd;"/>


                </li>


            </ul>
      
         


      </div>



    </div>

</template>











<script>
export default {
  name: 'Magicmodify',
  data () {
    return {
     
    }
  },
  mounted(){

      $("#xiala").attr("disabled","disabled").css("background-color","#EEEEEE;");

  }
}
</script>
<style scoped>

body{
  background: #ecf0f5;
}

.depat{
  width:100%;
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
 
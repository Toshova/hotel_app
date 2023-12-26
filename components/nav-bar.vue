<template>
        <div class="nav_container">     
            <button id="room_search_btn">Поиск номеров</button>
            <div class="timeblock">
                <p>12:45</p>
            
            <div>
                <p id="heading"> 10.01.2021 Ташкент</p>
            </div>   
        </div>
        
        <div class="right_block">
            <div class="alarm">
                <button id="alarm_btn">
                    <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M10.418 3.75C10.418 3.51988 10.2314 3.33333 10.0013 3.33333C9.7712 3.33333 9.58465 3.51988 9.58465 3.75V4.59682C7.82268 4.71347 6.85936 5.56914 6.35691 6.46239C6.09422 6.92939 5.96476 7.39232 5.90038 7.73571C5.86802 7.90826 5.85164 8.05313 5.84331 8.15673C5.83914 8.2086 5.83698 8.25034 5.83586 8.28028C5.83529 8.29526 5.83499 8.30731 5.83483 8.31621L5.83468 8.3272L5.83465 8.33088L5.83465 8.33226L5.83465 8.33333V12.7441L4.29002 14.2887C4.17085 14.4079 4.13521 14.5871 4.1997 14.7428C4.26419 14.8985 4.41612 15 4.58465 15H7.96586C8.00055 15.1719 8.06162 15.3856 8.1703 15.603C8.29918 15.8608 8.49905 16.1312 8.80665 16.3363C9.11685 16.5431 9.51174 16.6667 10.0013 16.6667C10.4909 16.6667 10.8858 16.5431 11.196 16.3363C11.5036 16.1312 11.7034 15.8608 11.8323 15.603C11.941 15.3856 12.0021 15.1719 12.0368 15H15.418C15.5865 15 15.7384 14.8985 15.8029 14.7428C15.8674 14.5871 15.8318 14.4079 15.7126 14.2887L14.168 12.7441L14.168 8.33333L14.168 8.33226L14.168 8.33088L14.168 8.3272L14.1678 8.31621C14.1676 8.30731 14.1673 8.29526 14.1668 8.28028C14.1657 8.25034 14.1635 8.2086 14.1593 8.15673C14.151 8.05313 14.1346 7.90826 14.1023 7.73571C14.0379 7.39232 13.9084 6.92939 13.6457 6.46239C13.1433 5.56914 12.18 4.71347 10.418 4.59682V3.75ZM6.66803 8.33133L6.66798 8.33447V12.9167C6.66798 13.0272 6.62408 13.1332 6.54594 13.2113L5.59057 14.1667H14.4121L13.4567 13.2113C13.3785 13.1332 13.3346 13.0272 13.3346 12.9167V8.33375L13.3346 8.33133L13.334 8.31151C13.3333 8.29262 13.3318 8.26275 13.3287 8.22348C13.3223 8.14478 13.3094 8.02924 13.2832 7.88929C13.2304 7.60768 13.1255 7.23727 12.9194 6.87094C12.5226 6.16557 11.7221 5.41667 10.0013 5.41667C8.28053 5.41667 7.48 6.16557 7.08322 6.87094C6.87716 7.23727 6.77224 7.60768 6.71944 7.88929C6.6932 8.02924 6.68029 8.14478 6.67397 8.22348C6.67081 8.26275 6.66931 8.29262 6.6686 8.31151L6.66803 8.33133ZM8.82438 15C8.8473 15.0749 8.87708 15.1532 8.91566 15.2303C8.99511 15.3892 9.10775 15.5355 9.2689 15.6429C9.42744 15.7486 9.65756 15.8333 10.0013 15.8333C10.3451 15.8333 10.5752 15.7486 10.7337 15.6429C10.8949 15.5355 11.0075 15.3892 11.087 15.2303C11.1255 15.1532 11.1553 15.0749 11.1783 15H8.82438Z" fill="#0066FF"/>
                    </svg>
                    <div>
                        <p>24</p> 
                    </div>
                       
                </button>
            </div>
            <div>
                <nuxt-link exact to="/profile_card">
                    <img  id='brunette' src="/brun.png"/>
                </nuxt-link> 
            </div>
        </div>
            
       
        </div>  
</template>
  
  <style scoped>
    *{
        position: sticky;
        top:0;
        left:0px;
        background-color: #FFFFFF;
        z-index: 2;

    }           
   .nav_container {
        display: flex;
        position: fixed;
        width: 100%;
        min-height: 64px;
        align-items: center;
        justify-content: space-between;  
                
   }

    button {
        width: 120px;
        height: 40px;  
        border: 1px solid #0066FF;  
        border-radius: 8px;
        color: #0066FF;
        font-size: 13px;
        font-weight: 500;
        line-height: 18px;
        text-align: center;
        font-family: 'SF Pro Display', sans-serif;  
    }
    
    #room_search_btn {
        margin-left: 256px;
    }
   
    .timeblock {
        display: flex;
        width: 315px;
        height: 20px;
        font-family: 'Digital-7 Mono', sans-serif;
        font-weight: 400;
        font-size: 34px;
        line-height: 20px;
        text-align: center;
        justify-content: space-between;
    }

    #heading {
        font-family: 'SF Pro Display', sans-serif;
        font-weight: 600;
        font-size: 22px;
        line-height: 20px;
        text-align: center;
        color:#8F97A3;
    }


    .right_block {
        display: flex;
        width:220px;
        margin-right: 36px;
        justify-content: end;
    }
    .alarm{
        display: flex;   
    }
    #alarm_btn{
        display: flex;
        align-items: center;
        justify-content: center;
        
    }
    #alarm_btn svg{
        margin-right: 8px;
    }
    #brunette {
        width: 40px;;
        height: 40px;
        margin-left: 24px;
    }



  </style>
  
  <script>
    export default {
    }
  </script>
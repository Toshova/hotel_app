<template>
    <div class="wrapper">

        <div class="print_menu  basic">
            <button class="s_btn">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M12 7C8.13401 7 5 10.134 5 14C5 15.1807 5.29191 16.2917 5.80709 17.2663C5.93614 17.5105 5.84284 17.813 5.59871 17.942C5.35458 18.0711 5.05205 17.9778 4.923 17.7337C4.33355 16.6185 4 15.3475 4 14C4 9.58172 7.58172 6 12 6C16.4183 6 20 9.58172 20 14C20 15.3475 19.6665 16.6185 19.077 17.7337C18.9479 17.9778 18.6454 18.0711 18.4013 17.942C18.1572 17.813 18.0639 17.5105 18.1929 17.2663C18.7081 16.2917 19 15.1807 19 14C19 10.134 15.866 7 12 7ZM7.62371 10.1707C7.80555 9.96293 8.12143 9.94187 8.32925 10.1237L12.3293 13.6237C12.5371 13.8056 12.5581 14.1214 12.3763 14.3293C12.1944 14.5371 11.8786 14.5581 11.6707 14.3763L7.67075 10.8763C7.46293 10.6944 7.44187 10.3786 7.62371 10.1707Z" fill="#0066FF"/>
                </svg>
            </button>
            <button class="s_btn">
                <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M6 6.5C6 5.11929 7.11929 4 8.5 4H15.5C16.8807 4 18 5.11929 18 6.5V17.5C18 18.8807 16.8807 20 15.5 20H8.5C7.11929 20 6 18.8807 6 17.5V6.5ZM8.5 5C7.67157 5 7 5.67157 7 6.5V17.5C7 18.3284 7.67157 19 8.5 19H15.5C16.3284 19 17 18.3284 17 17.5V6.5C17 5.67157 16.3284 5 15.5 5H8.5ZM13 9.5C13 9.22386 13.2239 9 13.5 9H15.5C15.7761 9 16 9.22386 16 9.5V11.5C16 11.7761 15.7761 12 15.5 12C15.2239 12 15 11.7761 15 11.5V10.8516L12.8796 13.3254C12.7867 13.4338 12.6519 13.4973 12.5092 13.4999C12.3665 13.5025 12.2294 13.444 12.1326 13.3391L11.0271 12.1415L8.89043 14.8123C8.71793 15.028 8.40328 15.0629 8.18765 14.8904C7.97202 14.7179 7.93706 14.4033 8.10957 14.1877L10.6096 11.0627C10.7006 10.9489 10.8367 10.8805 10.9823 10.8753C11.128 10.8702 11.2686 10.9288 11.3674 11.0359L12.4862 12.2479L14.4129 10H13.5C13.2239 10 13 9.77614 13 9.5Z" fill="#0066FF"/>
                </svg>
            </button>
            <button id="btn_2">
                <p>Распечатать</p>
            </button>
        </div>

        <div class="dashboard basic">
            <div class="card basic">
                <svg width="80" height="80" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M47.4655 9.5C47.4655 8.67157 48.1371 8 48.9655 8H60.5C67.9558 8 74 14.0442 74 21.5V58.5C74 65.9558 67.9558 72 60.5 72H47.8448C47.0164 72 46.3448 71.3284 46.3448 70.5C46.3448 69.6716 47.0164 69 47.8448 69H60.5C66.299 69 71 64.299 71 58.5V21.5C71 15.701 66.299 11 60.5 11H48.9655C48.1371 11 47.4655 10.3284 47.4655 9.5ZM34.508 25.3347C35.1209 24.7773 36.0696 24.8224 36.627 25.4352L48.9546 38.9908C49.4749 39.563 49.4749 40.437 48.9546 41.0092L36.627 54.5648C36.0696 55.1776 35.1209 55.2227 34.508 54.6653C33.8951 54.1079 33.8501 53.1592 34.4075 52.5463L44.4532 41.5H7.5C6.67157 41.5 6 40.8284 6 40C6 39.1716 6.67157 38.5 7.5 38.5H44.4532L34.4075 27.4536C33.8501 26.8408 33.8951 25.8921 34.508 25.3347Z" fill="#00CC99"/>
                </svg>
                <div class="card_text">
                    <p class="big_digit">18</p>
                    <p class="grey s_font">Заезжающих сегодня</p>
                </div>
            </div>

            <div class="card basic">
                <svg width="80" height="80" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M47.4655 9.5C47.4655 8.67157 48.1371 8 48.9655 8H60.5C67.9558 8 74 14.0442 74 21.5V58.5C74 65.9558 67.9558 72 60.5 72H47.8448C47.0164 72 46.3448 71.3284 46.3448 70.5C46.3448 69.6716 47.0164 69 47.8448 69H60.5C66.299 69 71 64.299 71 58.5V21.5C71 15.701 66.299 11 60.5 11H48.9655C48.1371 11 47.4655 10.3284 47.4655 9.5ZM20.8368 25.3347C21.4497 25.8921 21.4947 26.8408 20.9373 27.4536L10.8916 38.5H47.8448C48.6733 38.5 49.3448 39.1716 49.3448 40C49.3448 40.8284 48.6733 41.5 47.8448 41.5H10.8916L20.9373 52.5463C21.4947 53.1592 21.4497 54.1079 20.8368 54.6653C20.2239 55.2227 19.2752 55.1776 18.7179 54.5648L6.39027 41.0092C5.86991 40.437 5.86991 39.563 6.39027 38.9908L18.7179 25.4352C19.2752 24.8224 20.2239 24.7773 20.8368 25.3347Z" fill="#FF0033"/>
                </svg>
                <div class="card_text">
                    <p class="big_digit">34</p>
                    <p class="grey s_font">Выезжающих сегодня</p>
                </div>
                
            </div>

            <div class="card basic">
                <svg width="80" height="80" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M27 34V21.0031L27.0002 20.9873C27.0005 20.9706 27.0011 20.942 27.0026 20.9021C27.0054 20.8222 27.0114 20.6976 27.0239 20.5347C27.049 20.2083 27.0999 19.7315 27.2031 19.1549C27.4107 17.9952 27.8232 16.4694 28.634 14.9597C29.4405 13.4579 30.6327 11.9859 32.4082 10.8838C34.1794 9.7845 36.6165 9 40 9C43.3835 9 45.8206 9.7845 47.5918 10.8838C49.3673 11.9859 50.5595 13.4579 51.366 14.9597C52.1768 16.4694 52.5893 17.9952 52.7969 19.1549C52.9001 19.7315 52.951 20.2083 52.9761 20.5347C52.9886 20.6976 52.9946 20.8222 52.9974 20.9021C52.9988 20.942 52.9995 20.9706 52.9998 20.9873L53 21V21.0014V21.003C53 21.003 53 22.5 54.5 22.5C56 22.5 56 21 56 21V20.9983L56 20.9962L56 20.9912L55.9999 20.9774L55.9993 20.9353C55.9987 20.9008 55.9976 20.8537 55.9955 20.7947C55.9913 20.6768 55.9831 20.5114 55.9673 20.3052C55.9357 19.8932 55.8733 19.3154 55.75 18.6263C55.5044 17.2548 55.0107 15.4056 54.009 13.5403C53.003 11.6671 51.4764 9.76411 49.1739 8.33491C46.8669 6.903 43.8665 6 40 6C36.1335 6 33.1331 6.903 30.8261 8.33491C28.5236 9.76411 26.997 11.6671 25.991 13.5403C24.9893 15.4056 24.4956 17.2548 24.25 18.6263C24.1267 19.3154 24.0643 19.8932 24.0327 20.3052C24.0169 20.5114 24.0087 20.6768 24.0045 20.7947C24.0024 20.8537 24.0013 20.9008 24.0007 20.9353L24.0001 20.9774L24 20.9912L24 20.9962L24 20.9983L24 21V34H19.5C14.2533 34 10 38.2533 10 43.5V64.5C10 69.7467 14.2533 74 19.5 74H60.5C65.7467 74 70 69.7467 70 64.5V43.5C70 38.2533 65.7467 34 60.5 34H53H27ZM19.5 37C15.9101 37 13 39.9101 13 43.5V64.5C13 68.0899 15.9101 71 19.5 71H60.5C64.0899 71 67 68.0899 67 64.5V43.5C67 39.9101 64.0899 37 60.5 37H19.5Z" fill="#0066FF"/>
                </svg>
                <div class="card_text">
                    <p class="big_digit">47</p>
                    <p class="grey s_font">Свободных мест сегодня</p>
                </div>
                
            </div>

            <div class="card basic">
                <svg width="80" height="80" viewBox="0 0 80 80" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd" d="M32.5 12C25.3203 12 19.5 17.8203 19.5 25C19.5 32.1797 25.3203 38 32.5 38C39.6797 38 45.5 32.1797 45.5 25C45.5 17.8203 39.6797 12 32.5 12ZM16.5 25C16.5 16.1634 23.6634 9 32.5 9C41.3366 9 48.5 16.1634 48.5 25C48.5 33.8366 41.3366 41 32.5 41C23.6634 41 16.5 33.8366 16.5 25ZM45 10.5C45 9.67157 45.6716 9 46.5 9C55.3366 9 62.5 16.1634 62.5 25C62.5 33.8366 55.3366 41 46.5 41C45.6716 41 45 40.3284 45 39.5C45 38.6716 45.6716 38 46.5 38C53.6797 38 59.5 32.1797 59.5 25C59.5 17.8203 53.6797 12 46.5 12C45.6716 12 45 11.3284 45 10.5ZM15.5 51C11.9101 51 9 53.9101 9 57.5V69.5C9 70.3284 8.32843 71 7.5 71C6.67157 71 6 70.3284 6 69.5V57.5C6 52.2533 10.2533 48 15.5 48H49.5C54.7467 48 59 52.2533 59 57.5V69.5C59 70.3284 58.3284 71 57.5 71C56.6716 71 56 70.3284 56 69.5V57.5C56 53.9101 53.0899 51 49.5 51H15.5ZM63 49.5C63 48.6716 63.6716 48 64.5 48C69.7467 48 74 52.2533 74 57.5V69.5C74 70.3284 73.3284 71 72.5 71C71.6716 71 71 70.3284 71 69.5V57.5C71 53.9101 68.0899 51 64.5 51C63.6716 51 63 50.3284 63 49.5Z" fill="#9900FF"/>
                </svg>
                <div class="card_text">
                    <p class="big_digit">189</p>
                    <p class="grey s_font">Проживающих сегодня</p>
                </div>
                
            </div>
        </div>

        <div class="l_graphic basic">

            <div class="head_section grey m_font basic">
               <p>Годовая загруженность гостиницы в %</p> 
            </div>
            <div class="charts basic">
               <graphic-one/>
            </div>
        </div>

        <div class="m_graphics basic">

            <div class="m_graphic">
                <div class="head_section grey m_font ">
                    <p>Выручка от продаж номеров</p>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M11 5C7.68629 5 5 7.68629 5 11C5 14.3137 7.68629 17 11 17C14.3137 17 17 14.3137 17 11C17 7.68629 14.3137 5 11 5ZM4 11C4 7.13401 7.13401 4 11 4C14.866 4 18 7.13401 18 11C18 12.7558 17.3535 14.3607 16.2856 15.5895C16.3095 15.6062 16.3323 15.6251 16.3536 15.6464L19.8536 19.1464C20.0488 19.3417 20.0488 19.6583 19.8536 19.8536C19.6583 20.0488 19.3417 20.0488 19.1464 19.8536L15.6464 16.3536C15.6251 16.3323 15.6062 16.3095 15.5895 16.2856C14.3607 17.3535 12.7558 18 11 18C7.13401 18 4 14.866 4 11ZM11 7.5C11.2761 7.5 11.5 7.72386 11.5 8V10.5H14C14.2761 10.5 14.5 10.7239 14.5 11C14.5 11.2761 14.2761 11.5 14 11.5H11.5V14C11.5 14.2761 11.2761 14.5 11 14.5C10.7239 14.5 10.5 14.2761 10.5 14V11.5H8C7.72386 11.5 7.5 11.2761 7.5 11C7.5 10.7239 7.72386 10.5 8 10.5H10.5V8C10.5 7.72386 10.7239 7.5 11 7.5Z" fill="#8F97A3"/>
                    </svg>

                </div>
                <div class="menu_info">
                    <select>
                        <option>Январь 2021</option>
                        <option>Февраль 2021</option>
                        <option>Март 2021</option>
                        <option>Апрель 2021</option>
                        <option>Май 2021</option>
                        <option>Июнь 2021</option>
                        <option>Июль 2021</option>
                        <option>Август 2021</option>
                        <option>Сентябрь 2021</option>
                        <option>Октябрь 2021</option>
                        <option>Ноябрь 2021</option>
                        <option>Декабрь 2021</option>
                    </select>

                </div>
                <div class="charts">
                    <graphic-two/>
                </div>
            </div>

            <div class="m_graphic">
                <div class="head_section grey m_font">
                    <p>Месячная загруженность в %</p>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M11 5C7.68629 5 5 7.68629 5 11C5 14.3137 7.68629 17 11 17C14.3137 17 17 14.3137 17 11C17 7.68629 14.3137 5 11 5ZM4 11C4 7.13401 7.13401 4 11 4C14.866 4 18 7.13401 18 11C18 12.7558 17.3535 14.3607 16.2856 15.5895C16.3095 15.6062 16.3323 15.6251 16.3536 15.6464L19.8536 19.1464C20.0488 19.3417 20.0488 19.6583 19.8536 19.8536C19.6583 20.0488 19.3417 20.0488 19.1464 19.8536L15.6464 16.3536C15.6251 16.3323 15.6062 16.3095 15.5895 16.2856C14.3607 17.3535 12.7558 18 11 18C7.13401 18 4 14.866 4 11ZM11 7.5C11.2761 7.5 11.5 7.72386 11.5 8V10.5H14C14.2761 10.5 14.5 10.7239 14.5 11C14.5 11.2761 14.2761 11.5 14 11.5H11.5V14C11.5 14.2761 11.2761 14.5 11 14.5C10.7239 14.5 10.5 14.2761 10.5 14V11.5H8C7.72386 11.5 7.5 11.2761 7.5 11C7.5 10.7239 7.72386 10.5 8 10.5H10.5V8C10.5 7.72386 10.7239 7.5 11 7.5Z" fill="#8F97A3"/>
</svg>
                </div>
                <div class="menu_info">
                    <select>
                        <option>Январь 2021</option>
                        <option>Февраль 2021</option>
                        <option>Март 2021</option>
                        <option>Апрель 2021</option>
                        <option>Май 2021</option>
                        <option>Июнь 2021</option>
                        <option>Июль 2021</option>
                        <option>Август 2021</option>
                        <option>Сентябрь 2021</option>
                        <option>Октябрь 2021</option>
                        <option>Ноябрь 2021</option>
                        <option>Декабрь 2021</option>
                    </select>

                </div>
                <div class="charts">
                    <graphic-three/>
                </div>
            </div>
        </div>

        <div class="m_graphics basic">
            <div class="m_graphic">
                <div class="head_section grey m_font">
                    <p>Соотношение резидентов и иностранцев</p> 
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
<path fill-rule="evenodd" clip-rule="evenodd" d="M11 5C7.68629 5 5 7.68629 5 11C5 14.3137 7.68629 17 11 17C14.3137 17 17 14.3137 17 11C17 7.68629 14.3137 5 11 5ZM4 11C4 7.13401 7.13401 4 11 4C14.866 4 18 7.13401 18 11C18 12.7558 17.3535 14.3607 16.2856 15.5895C16.3095 15.6062 16.3323 15.6251 16.3536 15.6464L19.8536 19.1464C20.0488 19.3417 20.0488 19.6583 19.8536 19.8536C19.6583 20.0488 19.3417 20.0488 19.1464 19.8536L15.6464 16.3536C15.6251 16.3323 15.6062 16.3095 15.5895 16.2856C14.3607 17.3535 12.7558 18 11 18C7.13401 18 4 14.866 4 11ZM11 7.5C11.2761 7.5 11.5 7.72386 11.5 8V10.5H14C14.2761 10.5 14.5 10.7239 14.5 11C14.5 11.2761 14.2761 11.5 14 11.5H11.5V14C11.5 14.2761 11.2761 14.5 11 14.5C10.7239 14.5 10.5 14.2761 10.5 14V11.5H8C7.72386 11.5 7.5 11.2761 7.5 11C7.5 10.7239 7.72386 10.5 8 10.5H10.5V8C10.5 7.72386 10.7239 7.5 11 7.5Z" fill="#8F97A3"/>
</svg>           
                </div>  
                <div class="menu_info">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M12 6C12.2761 6 12.5 6.22386 12.5 6.5V8.53544C14.0328 8.7547 15.2453 9.96715 15.4646 11.5H17.5C17.7761 11.5 18 11.7239 18 12C18 12.2761 17.7761 12.5 17.5 12.5H15.4646C15.2453 14.0328 14.0328 15.2453 12.5 15.4646V17.5C12.5 17.7761 12.2761 18 12 18C11.7239 18 11.5 17.7761 11.5 17.5V15.4646C9.96715 15.2453 8.7547 14.0328 8.53544 12.5H6.5C6.22386 12.5 6 12.2761 6 12C6 11.7239 6.22386 11.5 6.5 11.5H8.53544C8.7547 9.96715 9.96715 8.7547 11.5 8.53544V6.5C11.5 6.22386 11.7239 6 12 6ZM12 9.5C10.6193 9.5 9.5 10.6193 9.5 12C9.5 13.3807 10.6193 14.5 12 14.5C13.3807 14.5 14.5 13.3807 14.5 12C14.5 10.6193 13.3807 9.5 12 9.5Z" fill="#0066FF"/>
                    </svg>
                    <span>Сегодня:  
                        <span style="color:#9900FF">своб - 22,0 %</span> | 
                        <span style="color:#00CC99">рез - 32,5 % </span>|
                        <span style="color:#0066FF">инос - 45,5 %</span> 
                    </span>

                </div>
                <div class="charts"> 
                    <column-chart/>
                </div>
            </div>

            <div class="m_graphic">
                <div class="head_section grey m_font">
                    <p>Топ 10 зарубежных государств</p>
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <path fill-rule="evenodd" clip-rule="evenodd" d="M11 5C7.68629 5 5 7.68629 5 11C5 14.3137 7.68629 17 11 17C14.3137 17 17 14.3137 17 11C17 7.68629 14.3137 5 11 5ZM4 11C4 7.13401 7.13401 4 11 4C14.866 4 18 7.13401 18 11C18 12.7558 17.3535 14.3607 16.2856 15.5895C16.3095 15.6062 16.3323 15.6251 16.3536 15.6464L19.8536 19.1464C20.0488 19.3417 20.0488 19.6583 19.8536 19.8536C19.6583 20.0488 19.3417 20.0488 19.1464 19.8536L15.6464 16.3536C15.6251 16.3323 15.6062 16.3095 15.5895 16.2856C14.3607 17.3535 12.7558 18 11 18C7.13401 18 4 14.866 4 11ZM11 7.5C11.2761 7.5 11.5 7.72386 11.5 8V10.5H14C14.2761 10.5 14.5 10.7239 14.5 11C14.5 11.2761 14.2761 11.5 14 11.5H11.5V14C11.5 14.2761 11.2761 14.5 11 14.5C10.7239 14.5 10.5 14.2761 10.5 14V11.5H8C7.72386 11.5 7.5 11.2761 7.5 11C7.5 10.7239 7.72386 10.5 8 10.5H10.5V8C10.5 7.72386 10.7239 7.5 11 7.5Z" fill="#8F97A3"/>
                    </svg>           
                </div>
                <div class="menu_info">
                    <select>
                        <option>Январь 2021</option>
                        <option>Февраль 2021</option>
                        <option>Март 2021</option>
                        <option>Апрель 2021</option>
                        <option>Май 2021</option>
                        <option>Июнь 2021</option>
                        <option>Июль 2021</option>
                        <option>Август 2021</option>
                        <option>Сентябрь 2021</option>
                        <option>Октябрь 2021</option>
                        <option>Ноябрь 2021</option>
                        <option>Декабрь 2021</option>
                    </select>

                </div>
                <div class=" bar_wrapper xs_font">
                    <div class="bar">
                        <barChart/>
                    </div>
                    <div class="bar_data">
                        <p>35 <span>|</span> 23,3 %</p>
                        <p>21 <span>|</span> 14,0 %</p>
                        <p>17 <span>|</span> 11,3 %</p>
                        <p>15 <span>|</span> 10,0 %</p>
                        <p>13 <span>|</span> 08,6 %</p>
                        <p>10 <span>|</span> 06,6 %</p>
                        <p>8 <span>|</span> 05,3 %</p>
                        <p>7 <span>|</span> 04,6 %</p>
                        <p>5 <span>|</span> 03,3 %</p>
                        <p>4 <span>|</span> 02,6 %</p>   
                    </div>  
                </div>
            </div>
        </div>  
       
</div>

</template>

<style scoped>
.menu_info{
    height:34px;
    text-align: start;
    margin: 14px 0 0 24px ;
    font-weight: 400;
    font-size: 15px;
    line-height: 20px;   
    display: flex; 
    flex-direction: row;
}


select{
    width: 120px;
    background: #FFFFFF url("/narrow.png")no-repeat right;
    display: block;
    appearance: none !important;
    border: transparent;
}


div {
    background-color: #FFFFFF;
}
.wrapper{
    background-color: #F0F6FF;
    width: 100%;
    height: max-content;
    display: flex;
    flex-direction: column;
    font-family: 'SF Pro Display', sans-serif;
}
.basic{
    margin-bottom: 12px;
    background-color: #FFFFFF;
    border-radius: 8px;
}
.print_menu{
    display: flex;
    width: 100%;
    height: 76px; 
    justify-content: end;
    align-items: center;  
}
.s_btn{
    justify-content: end;
    align-items: center;
    width: 48px;
    height: 48px;
    border: 1px solid #0066FF;
    border-radius: 8px;
    margin-right: 24px;
}
.s_btn svg{
    margin-left: 12px;
}

#btn_2 {
     background-color: #0066FF;
     color: #FFFFFF;
     border-radius: 8px;
     margin-right: 24px;
     width: 180px;
     height: 48px;
 }

 .dashboard{
    display: flex;
    flex-direction: row;
    background-color: transparent;
    height: 108px;
    justify-content: space-between;   
 }
 .card{
    display: flex;
    width: 24.5%;
    height: 108px;
    align-items: center;
    justify-content: space-around;
 }
 .big_digit{
    display: flex;
    font-weight: 600;
    font-size: 34px;
    line-height: 40px;
    color: #08162B;
    justify-content: end;
    margin-bottom: 20px;   
 }
 .xs_font{
    font-weight: 400;
    font-size: 13px;
    line-height: 18px;   
}

.s_font{
    font-weight: 500;
    font-size: 15px;
    line-height: 20px;   
}
.m_font {
    font-weight: 600;
    font-size: 17px;
    line-height: 20px;  
}
.grey{
    color:#8F97A3   
}
.l_graphic{
    display: flex;
    flex-direction: column;
    min-height: 406px;   
}

.m_graphics{
    width: 100%;
    height: 408px;
    display: flex;
    background-color: transparent;
    justify-content: space-between;   
}

.m_graphic {
    display: flex;
    flex-direction: column;
    text-align: center;  
    height: 408px;
    width: 49.5%;
    border-radius: 8px;
}
.head_section{
    display: flex;
    justify-content: space-between;
    border-bottom: 1px #D5D8DD solid;
    border-radius: 0px;
    min-height: 48px;
    align-items: center;
    border-radius: 8px 8px 0 0 ;
}
.head_section p{
    margin-left: 24px;
}

.head_section svg{
    margin-right: 24px;
}

.charts{
    margin-left: 10px;
}
.bar_wrapper{
display: flex;
width: 100%
}

.bar {
    width: 80%;
}
.bar_data{
    width:20%;
    height: 265px;
    color: #0066FF;
    display: flex;
    flex-direction: column;
    margin: 20px 0;
    justify-content: space-between;   
}

.bar_data span{
    color: #08162B
}
.bar_data {
   
    font-weight: 400;
    font-size: 13px;
    line-height: 18px;
}
</style>


<script>
import graphicOne from '../components/graphic-one.vue';
import graphicTwo from '../components/graphic-two.vue';
import graphicThree from '../components/graphic-three.vue';
import columnChart from '../components/column-chart.vue';
import barChart from '../components/bar-chart.vue';


export default {
    components: { 
        graphicOne, graphicTwo, graphicThree, columnChart, barChart
    },
}

</script>
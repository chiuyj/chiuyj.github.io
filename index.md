<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Web Design_final</title>
    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"> 
    <link rel="stylesheet" type="text/css" href="milestone4.css">
</head>

<body>
    <!-- Page 1 -->
    <div id="page1">
        <!-- Head (Navigator) Section -->
            <div class="col-12 nav"></div>

        <!-- Content Section -->
        <div style="position: relative; left: 7%">
            <!--黃色牌子-->
            <div class="col-3"></div><!--留白--->
            <div class="title col-5">
                <p>你適合養什麼樣的寵物？</p>
                <p>#領養代替購買#愛牠不要棄養牠</p>
            </div>
            
            <!--狗狗圖片-->
            <div class="row">
            <div class="col-3"></div><!--留白--->
                <img class="col-7" alt="page1-img" src="image/page1.png" style="width: 1200px; height: 750px; margin: -130px 0px -70px 50px;">
            </div>

            <!--開始 按鈕-->
            <div class="row">
            <div class="col-4"></div><!--留白--->
                <button class="btn col-3" id="p1_to_p2">
                    CLICK HERE TO START
                </button>
            </div>
        </div>
        <!-- Footer Section -->
            <div class="col-12 footer"></div>
    </div>

    <!-- Page 2 -->
    <div id="page2">
        <div class="row">
            <!-- Head (Navigator) Section -->
            <div class="col-12 nav"></div>
            <!-- Content Section -->
            <div class="col-12" style="position: relative;">
                <!--背景圖片-->
                <img class="col-12" src="image/page2.png" style="width:1450px; height:720px; position: relative; z-index: 1;">
                <!--question and buttons-->
                <div class="col-12" style="position: absolute; z-index: 2;">
                    <!--題目-->
                    <div id="qs1">
                        <h1>個性與興趣評估（可多選）
                        </h1>
                    </div> 
                    <!--第一行按鈕-->
                    <div id="flex1">
                        <div id="button" class="dog">
                            <h3>樂天</h3>
                        </div>
                        <div id="button" class="cat">
                            <h3>安靜</h3>
                        </div>
                        <div id="button" class="cat">
                            <h3>內向</h3>
                        </div>
                    </div>
                    <!--第二行按鈕-->
                    <div id="flex1">
                        <div id="button" class="dog">
                            <h3>喜歡運動</h3>
                        </div>
                        <div id="button" class="dog">
                            <h3>喜歡戶外</h3>
                        </div>
                        <div id="button" class="cat">
                            <h3>喜歡閱讀</h3>
                        </div>
                    </div>
                    <!--NEXT按鈕-->
                    <div class="next" id="p2_to_p3">
                        NEXT
                    </div>
                </div>
            </div>
            <!-- Footer Section -->
            <div class="col-12 footer"></div>
        </div>
    </div>

    <!-- Page 3 -->
    <div id="page3">
        <div class="row">
            <!-- Head (Navigator) Section -->
            <div class="col-12 nav"></div>
            <!-- Content Section -->
            <div class="col-12" style="position: relative;">
                <!--背景圖片-->
                <img class="col-12" src="image/page3.png" style="width:1450px; height:720px; position: relative; z-index: 1;">
                <!--question and buttons-->
                <div class="col-12" style="position: absolute; z-index: 2;">
                    <!--題目-->
                    <div id="qs2">
                        <h1>每月最高寵物花費預算</h1>
                    </div>
                    <!--第一行按鈕-->
                    <div id="flex2">
                        <div id="button" class="cat p3">
                            <h3>1000元以下</h3>
                        </div>
                        <div id="button" class="cat p3">
                            <h3>1000~1500元</h3>
                        </div>
                        <div id="button" class="smallDog p3">
                            <h3>1500~2000元</h3>
                        </div>
                    </div>
                    <!--第二行按鈕-->
                    <div id="flex2">
                        <div id="button" class="smallDog p3">
                            <h3>2000~5000元</h3>
                        </div>
                        <div id="button" class="middleDog p3">
                            <h3>5000~7000元</h3>
                        </div>
                        <div id="button" class="bigDog p3">
                            <h3>7000元以上</h3>
                        </div>
                    </div>
                    <!--NEXT按鈕-->
                    <div class="next" id="p3_to_p4">
                        NEXT
                    </div>
                </div>
            </div>
            <!-- Footer Section -->
            <div class="col-12 footer"></div>
        </div>
    </div>

    <!-- Page 4 -->
    <div id="page4">
        <div class="row">
            <!-- Head (Navigator) Section -->
            <div class="col-12 nav"></div>
            <!-- Content Section -->
            <div class="col-12" style="position: relative;">
                <!--背景圖片-->
                <img class="col-12" src="image/page4.png" style="width:1490px; height:750px; position: relative; z-index: 1;">
                <!--question and buttons-->
                <div class="col-12" style="position: absolute; z-index: 2;">
                    <!--題目-->
                    <div id="qs3">
                        <h1>平均外出運動時間（上下排各選一）</h1>
                    </div>
                    <!--第一行按鈕-->
                    <div id="flex3">
                        <div id="button" class="cat btnGroup1" style="width:160px;">
                            <h3>少於30分鐘</h3>
                        </div>
                        <div id="button" class="smallDog btnGroup1" style="width:160px;">
                            <h3>30分到1小時</h3>
                        </div>
                        <div id="button" class="middleDog btnGroup1" style="width:160px;">
                            <h3>1小時以上</h3>
                        </div>
                        <div id="button" class="bigDog btnGroup1" style="width:160px;">
                            <h3>1小時到2小時</h3>
                        </div>
                    </div>
                    <!--第二行按鈕-->
                    <div id="flex3">
                        <div id="button" class="cat btnGroup2" style="width:160px;">
                            <h3>一週一次</h3>
                        </div>
                        <div id="button" class="smallDog btnGroup2" style="width:160px;">
                            <h3>一週二到三次</h3>
                        </div>
                        <div id="button" class="middleDog btnGroup2" style="width:160px;">
                            <h3>一週四到五次</h3>
                        </div>
                        <div id="button" class="bigDog btnGroup2" style="width:160px;">
                            <h3>一週六次以上</h3>
                        </div>
                    </div>
                    <!--result按鈕-->
                    <div class="next" id="p4_to_p5">
                        RESULT
                    </div>
                </div>
            </div>
            <!-- Footer Section -->
            <div class="col-12 footer"></div>
        </div>
    </div>

    <!-- Page 5 -->
    <div id="page5">
        <div class="row">
            <!-- Head (Navigator) Section -->
            <div class="col-12 nav"></div>
        	<!-- Left Section -->
        	<div class="col-3">
    			<!--分析結果title-->
    			<div class="result_title">
    				<h1>分析結果</h1>
    			</div>
    			<!--圖片-->
    		    <div class="result_pic">
    				<img src="image/dog0.png" style="width:180px; height:150px;">
    			</div>
    			<!--結果content-->
    			<div class="row">
                    <div class="col-1"></div>
    				<div class="col-10 result_content">
    					<h4>～你適合～</h4>
    					<h1 id="suggestPetLabel">大型犬</h1>
                        <div class="row">
                            <div class="col-1"></div>
                            <div class="tryagain col-10" id="p5_to_p1">
                                TRY AGAIN
                            </div>
                        </div>
    				</div>
    			</div>
        	</div>
    		<!--Right Section-->
    		<div class="col-8" style="position: relative;">
                <!--外框-->
                <div class="square col-12" style="position: relative;">
                <!--圓形1-->
                    <div class="pie col-5" style="background: #008080; margin:0px 20px 5px 50px; position: relative; z-index: 1;">
    				   <img src="image/dog4.png" style="width:250px; height: 191px; position: absolute; z-index: 2; left: 18%; top: 25%;">
                    </div>
                <!--圓形2-->
                    <div class="pie col-5" style="background: #7400A1; margin:0px 0px 5px 10px; position: relative; z-index: 1;">
    				   <img src="image/cat4.png" style="width:230px; height: 170px; position: absolute; z-index: 2; left: 20%; top: 27%;">
                    </div>
                <!--click-->
                    <div class="row">
                        <!--click for more1-->
                            <div class="click col-5" style="margin: 5px 50px 5px 140px;" id="p5_to_p6">
                            CLICK TO SEE MORE
                            </div>
        			  	<!--click for more2-->
        			  		<div class="click col-5" style="margin: 5px 0px 5px 150px;" id="p5_to_p7">
        			  		CLICK TO SEE MORE
        					</div>
                    </div>
                </div>
    		</div>
            <!-- Footer Section -->
            <div class="col-12 footer"></div>
        </div>
    </div>

    <!-- Page 6 - Dpg -->
    <div id="page6">
        <!-- Head (Navigator) Section -->
        <div class="col-12 nav">
        	<div class="col-1"></div>
            <div class="col-1">
                <img src="image/dog1.png" alt="dog1" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/dog2.png" alt="dog2" style="width: 100px; height: 100px">
            </div>
            <div class="col-2">
                <img src="image/dog3.png" alt="dog3" style="width: 100px; height: 100px">
            </div>
            <div class="col-3">
        		<h1>如果想養狗狗...</h1>
        	</div>
            <div class="col-1">
                <img src="image/dog4.png" alt="dog4" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/dog5.png" alt="dog5" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/dog6.png" alt="dog6" style="width: 100px; height: 100px">
            </div>  
        </div>
        
        <!-- Content Section -->
        <div class="row">
        
            <!-- Left Section -->
            <div class="col-9">
                <div class="col-12 menu">
                    <h1>一、基本資訊</h1>
                    <ul>
                        <table>
                            <tr>
                                <th rowspan="4"><li>大型犬</li></th>
                                <tr>
                                    <th>運動量</th>
                                    <td style="text-align: left;">建議：一天散步2-3次，每次一小時</td>
                                </tr>
                            </tr>
                            <tr>
                                <th rowspan="2">食量</th>
                                <td style="text-align: left;">45kg 以上：7000 kcal/日</td>  
                            </tr>
                            <tr>
                                <td style="text-align: left;">30-45kg：4350-6625 kcal/日</td>
                            </tr>
                            <tr>
                                <th rowspan="3"><li>中型犬</li></th>
                                <tr>
                                    <th>運動量</th>
                                    <td style="text-align: left;">建議：一天散步2次，每次20-30分鐘</td>
                                </tr>
                            </tr>
                            <tr>
                                <th rowspan="2">食量</th>
                                <td style="text-align: left;">15-30kg：2175-4350 kcal/日</td> 
                            </tr>
                            <tr>
                                <th rowspan="5"><li>小型犬</li></th>
                                <tr>
                                    <th>運動量</th>
                                    <td style="text-align: left;">建議：一天散步1-2次，每次5-10分鐘</td>
                                </tr>
                            </tr>
                            <tr>
                                <th rowspan="2">食量</th>
                                <td style="text-align: left;">小於 5kg：400 kcal/日</td>    
                            </tr>
                            <tr>
                                <td style="text-align: left;">5-15kg：400-2175 kcal/日</td>
                            </tr>   
                            
                        </table>
                    </ul>
                    <h1>二、補充資料</h1>
                    <ul>
                        <table>
                            <tr>
                                <th><li>結紮</li></th>
                                <th style="text-align: left;">
                                    優點：杜絕意外交配的可能、預防生殖器疾病、減少基因不良產下品種狗。<br>
                                    缺點：手術風險、體重增加、尿失禁。
                                </br>費用：公狗約1500元，母狗約2500元。
                                </th>
                            </tr>
                            <tr>
                                <th><li>晶片</li></th>
                                <th style="text-align: left;">加大找回走失寵物狗的機率，無明顯副作用。</br>
                                    費用：植入一次300元，登記500元到1000元不等。</th>
                            </tr>                       
                            <tr>
                                <th><li>美容</li></th>
                                <th style="text-align: left;">定期洗澡、清理耳朵、剪指甲、造型，減少患皮膚病的機率，讓寵物更健康。</br>
                                小美容（不含造型）/大美容價格：</br>小型犬：500元起/1000元起，中型犬：800元起/1600元起，大型犬：1200元起/2400元起。</th>
                            </tr>
                        </table>
                    </ul>
                </div>
            </div>
            
            
            <!-- Right Section -->
            <div class="col-3">
                <h1>相關網站</h1>
                <!--全國動物收容系統-->
                <div class="row">
                    <div class="fake-box">
                        <a href="https://asms.coa.gov.tw/Amlapp/App/Default.aspx">
                        <img src="image/website1.png" alt="website1全國動物收容系統" style="width: 200px; height: 200px;" >
                        </a>
                    </div>
                </div>
                <!--流浪動物花園-->
                <div class="row">
                    <div class="fake-box">
                        <a href="http://www.doghome.org.tw/phpbb2/indexnew.php">
                        <img src="image/website2.jpg" alt="website2流浪動物花園" style="width: 200px; height: 200px;">
                        </a>
                    </div>
                </div>
                
                <button class="btn" id="p6_to_p5">
                     BACK TO PREVIOUS PAGE
                </button>
                
            </div>
        </div>

        <!-- Footer Section -->
        <div class="col-12 footer"></div>
    </div>

    <!-- Page 7 - Cat -->
    <div id="page7">
        <!-- Head (Navigator) Section -->
        <div class="col-12 nav">
        	<div class="col-1"></div>
            <div class="col-1">
                <img src="image/cat1.png" alt="cat1" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/cat2.png" alt="cat2" style="width: 100px; height: 100px">
            </div>
            <div class="col-2">
                <img src="image/cat3.png" alt="cat3" style="width: 100px; height: 100px">
            </div>
            <div class="col-3">
        		<h1>如果想養貓貓...</h1>
        	</div>
            <div class="col-1">
                <img src="image/cat4.png" alt="cat4" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/cat5.png" alt="cat5" style="width: 100px; height: 100px">
            </div>
            <div class="col-1">
                <img src="image/cat6.png" alt="cat6" style="width: 100px; height: 100px">
            </div>
    	</div>
        
        
        <!-- Content Section -->
    	<div class="row">
            <!-- Left Section -->
            <div class="col-9">
                <div class="col-12 menu">
                    <h1>一、基本資訊</h1>
                    <ul>
                        <table>
                            <tr>
                                <th>食量</th>
                                <th>體重(kg)</th>
                                <td>克/每天</td>
                            </tr>
                            <tr>
                                <th rowspan="3"><li>小型貓</li></th>
                                <tr>
                                    <th>2kg</th>
                                    <td>70g</td>
                                </tr>
                            </tr>
                            <tr>
                                <th>3kg</th>
                                <td>90g</td>    
                            </tr>
                            <tr>
                                <th rowspan="4"><li>中型貓</li></th>
                                <tr>
                                    <th>4kg</th>
                                    <td>120g</td>
                                </tr>
                            </tr>
                            <tr>
                                <th>5kg</th>
                                <td>140g</td>   
                            </tr>
                            <tr>
                                <th>6kg</th>
                                <td>160g</td>   
                            </tr>
                            <tr>
                                <th rowspan="4"><li>大型貓</li></th>
                                <tr>
                                    <th>7kg</th>
                                    <td>180g</td>
                                </tr>
                            </tr>
                            <tr>
                                <th>8kg</th>
                                <td>200g</td>   
                            </tr>
                            <tr>
                                <th>9kg</th>
                                <td>220g</td>   
                            </tr>
                        </table>
                    </ul>
                    <h1>二、補充資料</h1>
                    <ul>
                        <table>
                            <tr>
                                <th><li>結紮</li></th>
                                <th style="text-align: left;">
                                    有效改善噴尿行為、穩定性情、降低分離焦慮症、預防疾病或腫瘤。<br>
                                    費用：公貓約1500元；母貓約3000元。
                                </th>
                            </tr>
                            <tr>
                                <th><li>晶片</li></th>
                                <th style="text-align: left;">
                                    加大找回走失寵物狗的機率，無明顯副作用。</br>
                                    費用：植入一次300元，登記500元到1000元不等。</th>
                            </tr>
                            <tr>
                                <th><li>美容</li></th>
                                <th style="text-align: left;">洗澡週期：三到四週，最長一個半月。</br>
                                費用：約300元到1000元/洗澡，剃毛約1000元。</th>
                            </tr>
                        </table>
                    </ul>
                </div>
            </div>
            
            
            <!-- Right Section -->
            <div class="col-3">
                <h1>相關網站</h1>
                <!--全國動物收容系統-->
                <div class="row">
                    <div class="fake-box">
                        <a href="https://asms.coa.gov.tw/Amlapp/App/Default.aspx">
                        <img src="image/website1.png" alt="website1全國動物收容系統" style="width: 200px; height: 200px;">
                        </a>
                    </div>
                </div>
                <!--流浪動物花園-->
                <div class="row">
                    <div class="fake-box">
                        <a href="http://www.doghome.org.tw/phpbb2/indexnew.php">
                        <img src="image/website2.jpg" alt="website2流浪動物花園" style="width: 200px; height: 200px;" >
                        </a>
                    </div>
                </div>

                <button class="btn" id="p7_to_p5">
                    BACK TO PREVIOUS PAGE
                </button>
                
            </div>
        </div>

        <!-- Footer Section -->
        <div class="col-12 footer"></div>
    </div>

    <script src="external.js"></script>
</body>
</html>

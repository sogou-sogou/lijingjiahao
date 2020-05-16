加浩版权
                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          
版权：https://bitbucket.org/sogou-jiahao/sogou.git
加浩码云内容为GitHub的备份文件
均为加浩版权




















<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">
    <base href="http://localhost:18444/numzl6pm5senx1rs9ikc5vhxkvubjcc2/">

    <title> 佛跳墙</title>
    
    <link href="static/sb/vendor/bootstrap/css/bootstrap.min.css" rel="stylesheet">

    
    <link href="static/sb/vendor/metisMenu/metisMenu.min.css" rel="stylesheet">

    
    <link href="static/sb/dist/css/sb-admin-2.min.css" rel="stylesheet">
    
    <link href="static/sb/dist/css/flag-icon.min.css" rel="stylesheet">

    
    <link href="static/sb/vendor/font-awesome/css/font-awesome.min.css" rel="stylesheet" type="text/css">

    <link href="static/sb/dist/css/style.css" rel="stylesheet" type="text/css">
    <script src="static/js/getBrowserInfo.js"></script>

    
        
            
            
        
    

    
    
    
    
    
    
    

    
        
            
                
                
            
        
        
            
        
    
    
    
    

</head>

<body>

<div id="wrapper">

    
    <nav class="navbar navbar-default navbar-static-top" role="navigation" style="margin-bottom: 0">
        
            
                
                
                
                
            
            
        
        

        <ul class="nav navbar-top-links navbar-right">
            <li>
                <a href="javascript:void(0)" id="download-nav" onclick='getMobileApp_fd();'>&nbsp;<i class="ff-icon icon-mobile-gif u-recovery"></i>获取手机APP</a>
            </li>
            
                
            
            <li>
                <a href="javascript:void(0)" id="account" onclick="accountBox()">
                    
                        
                        游客，您好
                        
                    
                    
                        <i class="ff-icon icon-arrow u-recovery"></i>
                    
                </a>
            </li>
            
        </ul>
        <div class="base-account">
            <div class="account-info">
                <div class="account-type"><i class="ff-icon icon-major"></i>
                    <span class="account_type">
                            
                        </span></div>
                <div class="email">
                    <div class="account-title">账号</div>
                    <div class="account-text">
                        vis107550702bi
                        
                            (系统分配)
                        
                    </div>
                </div>
                
                <div class="date">
                    <div class="account-title "><span class="account_date">
                            
                        </span></div>
                    <div class="account-text end_date"></div>
                </div>
                <div class="equipment-list">
                    <div class="equipment-title">
                        <i class="ff-icon icon-equipment"></i>绑定手机/邮箱后可同时在 3 个设备上使用<br/>已登录设备如下：
                    </div>
                    
                </div>
            </div>
        
            <div class="bindaccount"><span class="bind-account-btn" onclick="show_bind_view()">绑定手机/邮箱</span></div>
        
        
            <div class="switchaccount"><span class="switch-btn" onclick="switchbtn()">切换账号</span></div>
        
        
        </div>
        

    

<div class="navbar-default sidebar" role="navigation">
     <div class="big-icon">
            <i class="icon-fotiaoqiang ff-icon"></i>
            佛跳墙
        </div>
    <div class="sidebar-nav navbar-collapse">
      <ul class="nav" id="side-menu">
        <li>
            <a href="connect" id="connect"><i class="ff-icon icon-home"></i>首页</a>
        </li>
      
          <li>
              <span class="bind-account-btn" onclick="show_bind_view()"><i class="ff-icon icon-bind"></i>绑定手机/邮箱</span>
          </li>
      
      <li>
          <span id="notice-sidebar" onclick="show_notice();"><i class="ff-icon icon-notice"></i>公告</span>
      </li>
      
        <li>
            <span id="update_pro"><i class="ff-icon icon-upgrade"></i><span id="update_pro_text" class="update_pro_text_cls" >
                
                    升级至专业版
                
                </span></span>
        </li>

        
            
        
          
              <li>
                  <span id="invite_fd" onclick="invite_fd();"><i class="ff-icon icon-profile"></i>
                      <span id="invite_fd_text">
              
                    邀请好友
                
                      </span>
              </span>
              </li>
              
          


          
          <li>
              <a href="https://gsoogsdafsle.github.io/wizard/faq_all.html" target="_blank"><i class="ff-icon icon-aq"></i>常见问题</a>
          </li>
          

          
          <li>
              <span id="download-sidebar" onclick='getMobileApp_fd();'><i class="ff-icon icon-mobile"></i>获取手机APP</span>
          </li>

          <li>
              <span id="check_update" onclick="check_update();"><i class="ff-icon icon-update"></i>检查更新</span>
          </li>
          <li>
              <span id="report_problem" onclick="show_report_problem_view()"><i class="ff-icon icon-problem-report"></i>问题反馈</span>
          </li>
          <li>
              <a href="settings"><i class="ff-icon icon-setting"></i>设置</a>
          </li>
        
        

        

      </ul>
    </div>
</div>

<div class="problem-report-div" onclick="show_report_problem_view()">
    问题反馈
</div>

<div class="msg-wrap" id="first-wrap">
    <div class="mask" id="closeMsg" onclick="closeMsg();">
        
        <div class="upgrade-pro" id="update">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            
            <div class="pro-box">
                <div class="pro-title update_pro_text_cls" id="upgrade-pro-title">
                
                    升级至专业版
                
                </div>
                <div >
                    <div class="free-box-upgrade">
                        <div class="free-title-upgrade center-cls">免费版</div>
                        <table>
                            <tr>
                                <td>网速</td>
                                <td>1KB/S</td>
                            </tr>
                            <tr>
                                <td>线路</td>
                                <td>随机</td>
                            </tr>
                            <tr>
                                <td>稳定性</td>
                                <td>不保障</td>
                            </tr>
                            <tr>
                                <td>高速流量</td>
                                <td>100MB体验</td>
                            </tr>
                            <tr>
                                <td>安全私密性</td>
                                <td>不保障</td>
                            </tr>
                            <tr>
                                <td>广告</td>
                                <td>有</td>
                            </tr>
                            <tr>
                                <td>服务</td>
                                <td>无</td>
                            </tr>
                            <tr>
                                <td>特权</td>
                                <td>无</td>
                            </tr>
                        </table>
                    </div>

                    <div class="pro-box-upgrade">
                        <div class="pro-title-upgrade center-cls">专业版</div>
                        <table>
                            <tr>
                                <td>网速</td>
                                <td>5000KB/S</td>
                            </tr>
                            <tr>
                                <td>线路</td>
                                <td>VIP专属线路</td>
                            </tr>
                            <tr>
                                <td>稳定性</td>
                                <td>100%稳定</td>
                            </tr>
                            <tr>
                                <td>高速流量</td>
                                <td>无限流量</td>
                            </tr>
                            <tr>
                                <td>安全私密性</td>
                                <td>100%安全</td>
                            </tr>
                            <tr>
                                <td>广告</td>
                                <td>无</td>
                            </tr>
                            <tr>
                                <td>服务</td>
                                <td>VIP专属客服</td>
                            </tr>
                            <tr>
                                <td>特权</td>
                                <td>续费折上折</td>
                            </tr>
                        </table>
                    </div>
                    <div class="upgrade-arrow"></div>
                </div>
                <div class="text_reason_strip">
                    
                </div>
                <div class="select-item">
                </div>
            </div>
        </div>
        
        <div class="pro-package" id="pro-package">
            <div class="close-box-btn" onclick="close_box_btn()"></div>
            <div class="gift-pic"></div>
            <div class="free-title"><span>重要提示：</span>亲爱的用户，您的免费高速流量已用完，当前的速度只有1KB/S，网速十分缓慢、卡顿，严重影响您的翻墙体验，建议您升级至专业版</div>
            <div class="btn-item center-cls">
                <button class="green-btn green-btn-2 free-to-pro">升级至专业版</button>
            </div>
            <div class="free-title">
                <a href="https://ftqmat.github.io/ftq_why/ftq_why.html" target="_blank"><span>为什么网速这么慢？ &gt;&gt;</span></a>
            </div>
            <div >
                <div class="free-box-upgrade">
                    <div class="free-title-upgrade center-cls">免费版</div>
                    <table>
                        <tr>
                            <td>网速</td>
                            <td>1KB/S</td>
                        </tr>
                        <tr>
                            <td>线路</td>
                            <td>随机</td>
                        </tr>
                        <tr>
                            <td>稳定性</td>
                            <td>不保障</td>
                        </tr>
                        <tr>
                            <td>高速流量</td>
                            <td>100MB体验</td>
                        </tr>
                        <tr>
                            <td>安全私密性</td>
                            <td>不保障</td>
                        </tr>
                        <tr>
                            <td>广告</td>
                            <td>有</td>
                        </tr>
                        <tr>
                            <td>服务</td>
                            <td>无</td>
                        </tr>
                        <tr>
                            <td>特权</td>
                            <td>无</td>
                        </tr>
                    </table>
                </div>

                <div class="pro-box-upgrade">
                    <div class="pro-title-upgrade center-cls">专业版</div>
                    <table>
                        <tr>
                            <td>网速</td>
                            <td>5000KB/S</td>
                        </tr>
                        <tr>
                            <td>线路</td>
                            <td>VIP专属线路</td>
                        </tr>
                        <tr>
                            <td>稳定性</td>
                            <td>100%稳定</td>
                        </tr>
                        <tr>
                            <td>高速流量</td>
                            <td>无限流量</td>
                        </tr>
                        <tr>
                            <td>安全私密性</td>
                            <td>100%安全</td>
                        </tr>
                        <tr>
                            <td>广告</td>
                            <td>无</td>
                        </tr>
                        <tr>
                            <td>服务</td>
                            <td>VIP专属客服</td>
                        </tr>
                        <tr>
                            <td>特权</td>
                            <td>续费折上折</td>
                        </tr>
                    </table>
                </div>
                <div class="upgrade-arrow"></div>
            </div>
        </div>
        
        <div class="login-box" id="login">
            <ul class="tabs">
                <li><a class="active" id="login_phone_btn" onclick="login_phone_btn()">手机登录</a></li>
                <li><a id="login_mail_btn" onclick="login_mail_btn()">邮箱登录</a></li>
            </ul>
            <div id="login-phone-div">
                <form method="post"  class="form signin-form">
                    <div class="u-pr">
                        <select name="country" id="c3">
                        <option value="86" selected> 中国+86 </option><option value="93" > 阿富汗+93 </option><option value="1890" > 多米尼加共和国+1890 </option><option value="1345" > 开曼群岛+1345 </option><option value="1246" > 巴巴多斯+1246 </option><option value="247" > 阿森松+247 </option><option value="374" > 亚美尼亚+374 </option><option value="1264" > 安圭拉岛+1264 </option><option value="1876" > 牙买加+1876 </option><option value="81" > 日本+81 </option><option value="962" > 约旦+962 </option><option value="7" > 哈萨克斯坦+7 </option><option value="254" > 肯尼亚+254 </option><option value="996" > 吉尔吉斯+996 </option><option value="856" > 老挝+856 </option><option value="371" > 拉脱维亚+371 </option><option value="297" > 阿鲁巴+297 </option><option value="961" > 黎巴嫩+961 </option><option value="266" > 莱索托+266 </option><option value="231" > 利比里亚+231 </option><option value="218" > 利比亚+218 </option><option value="423" > 列支敦士登+423 </option><option value="370" > 立陶宛+370 </option><option value="352" > 卢森堡+352 </option><option value="853" > 澳门+853 </option><option value="389" > 马其顿共和国+389 </option><option value="261" > 马达加斯加+261 </option><option value="61" > 澳大利亚+61 </option><option value="265" > 马拉维+265 </option><option value="60" > 马来西亚+60 </option><option value="960" > 马尔代夫+960 </option><option value="223" > 马里+223 </option><option value="356" > 马耳他+356 </option><option value="222" > 毛里塔尼亚+222 </option><option value="230" > 毛里求斯+230 </option><option value="52" > 墨西哥+52 </option><option value="43" > 奥地利+43 </option><option value="691" > 密克罗尼西亚联邦+691 </option><option value="373" > 摩尔多瓦+373 </option><option value="377" > 摩纳哥+377 </option><option value="976" > 蒙古+976 </option><option value="382" > 黑山共和国+382 </option><option value="212" > 摩洛哥+212 </option><option value="258" > 莫桑比克+258 </option><option value="95" > 缅甸+95 </option><option value="264" > 纳米比亚+264 </option><option value="994" > 阿塞拜疆共和国+994 </option><option value="977" > 尼泊尔+977 </option><option value="31" > 荷兰+31 </option><option value="599" > 荷属安德烈斯群岛+599 </option><option value="687" > 新喀里多尼亚+687 </option><option value="64" > 新西兰+64 </option><option value="505" > 尼加拉瓜+505 </option><option value="227" > 尼日尔+227 </option><option value="234" > 尼日利亚+234 </option><option value="1242" > 巴哈马+1242 </option><option value="47" > 挪威+47 </option><option value="968" > 阿曼+968 </option><option value="680" > 帕劳+680 </option><option value="92" > 巴勒斯坦+92 </option><option value="507" > 巴拿马+507 </option><option value="675" > 巴布亚新几内亚+675 </option><option value="595" > 巴拉圭+595 </option><option value="51" > 秘鲁+51 </option><option value="63" > 菲律宾+63 </option><option value="973" > 巴林+973 </option><option value="48" > 波兰+48 </option><option value="351" > 葡萄牙+351 </option><option value="1787" > 波多黎各+1787 </option><option value="974" > 卡塔尔+974 </option><option value="262" > 留尼旺岛+262 </option><option value="40" > 罗马尼亚+40 </option><option value="7" > 俄罗斯+7 </option><option value="250" > 卢旺达+250 </option><option value="880" > 孟加拉共和国+880 </option><option value="378" > 圣马力诺+378 </option><option value="239" > 圣多美和普林西比+239 </option><option value="966" > 沙特阿拉伯+966 </option><option value="221" > 塞内加尔+221 </option><option value="381" > 塞尔维亚共和国+381 </option><option value="248" > 塞舌尔+248 </option><option value="232" > 塞拉利昂+232 </option><option value="65" > 新加坡+65 </option><option value="421" > 斯洛伐克+421 </option><option value="386" > 斯洛文尼亚+386 </option><option value="252" > 索马里+252 </option><option value="27" > 南非+27 </option><option value="82" > 韩国+82 </option><option value="34" > 西班牙+34 </option><option value="94" > 斯里兰卡+94 </option><option value="211" > 苏丹+211 </option><option value="375" > 白俄罗斯+375 </option><option value="597" > 苏里南+597 </option><option value="268" > 斯威士兰+268 </option><option value="46" > 瑞典+46 </option><option value="41" > 瑞士+41 </option><option value="963" > 叙利亚+963 </option><option value="886" > 台湾+886 </option><option value="992" > 塔吉克斯坦+992 </option><option value="255" > 坦桑尼亚+255 </option><option value="66" > 泰国+66 </option><option value="243" > 刚果民主共和国+243 </option><option value="355" > 阿尔巴尼亚+355 </option><option value="32" > 比利时+32 </option><option value="228" > 多哥+228 </option><option value="676" > 汤加+676 </option><option value="1868" > 特立尼达和多巴哥+1868 </option><option value="216" > 突尼斯+216 </option><option value="90" > 土耳其+90 </option><option value="993" > 土库曼斯坦+993 </option><option value="501" > 伯利兹+501 </option><option value="256" > 乌干达+256 </option><option value="380" > 乌克兰+380 </option><option value="44" > 英国+44 </option><option value="1" > 美国+1 </option><option value="598" > 乌拉圭+598 </option><option value="998" > 乌兹别克斯坦+998 </option><option value="678" > 瓦努阿图+678 </option><option value="58" > 委内瑞拉+58 </option><option value="229" > 贝宁共和国+229 </option><option value="84" > 越南+84 </option><option value="967" > 也门+967 </option><option value="260" > 赞比亚+260 </option><option value="263" > 津巴布韦+263 </option><option value="1441" > 百慕大群岛+1441 </option><option value="975" > 不丹+975 </option><option value="591" > 玻利维亚+591 </option><option value="387" > 波斯尼亚和黑塞哥维那+387 </option><option value="267" > 博茨瓦纳+267 </option><option value="55" > 巴西+55 </option><option value="213" > 阿尔及利亚+213 </option><option value="673" > 文莱+673 </option><option value="359" > 保加利亚+359 </option><option value="226" > 布基纳法索+226 </option><option value="257" > 布隆迪+257 </option><option value="855" > 柬埔寨+855 </option><option value="237" > 喀麦隆+237 </option><option value="1" > 加拿大+1 </option><option value="238" > 佛得角+238 </option><option value="236" > 中非共和国+236 </option><option value="235" > 乍得+235 </option><option value="56" > 智利+56 </option><option value="57" > 哥伦比亚+57 </option><option value="242" > 刚果+242 </option><option value="682" > 库克群岛+682 </option><option value="506" > 哥斯达黎加+506 </option><option value="385" > 克罗地亚+385 </option><option value="376" > 安道尔共和国+376 </option><option value="53" > 古巴+53 </option><option value="357" > 塞浦路斯+357 </option><option value="420" > 捷克共和国+420 </option><option value="45" > 丹麦+45 </option><option value="253" > 吉布提+253 </option><option value="593" > 厄瓜多尔+593 </option><option value="244" > 安哥拉+244 </option><option value="20" > 埃及+20 </option><option value="503" > 萨尔瓦多+503 </option><option value="240" > 赤道几内亚+240 </option><option value="291" > 厄立特里亚+291 </option><option value="372" > 爱沙尼亚+372 </option><option value="251" > 埃塞俄比亚+251 </option><option value="500" > 福克兰群岛+500 </option><option value="298" > 法罗群岛+298 </option><option value="679" > 斐济+679 </option><option value="358" > 芬兰+358 </option><option value="33" > 法国+33 </option><option value="594" > 法属圭亚那+594 </option><option value="689" > 法属波利尼西亚+689 </option><option value="241" > 加蓬+241 </option><option value="220" > 冈比亚+220 </option><option value="995" > 格鲁吉亚+995 </option><option value="49" > 德国+49 </option><option value="233" > 加纳+233 </option><option value="350" > 直布罗陀+350 </option><option value="30" > 希腊+30 </option><option value="1268" > 安提瓜和巴布达+1268 </option><option value="590" > 瓜德罗普岛+590 </option><option value="1671" > 关岛+1671 </option><option value="502" > 危地马拉+502 </option><option value="224" > 巴布亚新几内亚+224 </option><option value="245" > 几内亚比绍共和国+245 </option><option value="592" > 圭亚那+592 </option><option value="509" > 海地+509 </option><option value="504" > 洪都拉斯+504 </option><option value="54" > 阿根廷+54 </option><option value="852" > 香港+852 </option><option value="36" > 匈牙利+36 </option><option value="354" > 冰岛+354 </option><option value="91" > 印度+91 </option><option value="62" > 印度尼西亚+62 </option><option value="98" > 伊朗+98 </option><option value="964" > 伊拉克+964 </option><option value="353" > 爱尔兰+353 </option><option value="972" > 以色列+972 </option><option value="39" > 意大利+39 </option>
                        </select>
                        <input class="inputng number-control" name="username" type="text" autofocus required id="p3" maxlength="15"
                               oninvalid="this.setCustomValidity('此字段为必须，请按提示输入')" oninput="setCustomValidity('')" type="text" placeholder="请输入手机"/>
                        <div class="error-msg" id="signin-form-err"></div>
                    </div>
                    <span>
                        <input class="inputng" placeholder='请输入验证码' name="password" type="text" value="" required style="width:210px;"
                               oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('验证码格式出错')}" oninput="setCustomValidity('')" pattern="^[ -~]{4,4}$"/>
                        <button class="get-verify-code" id="get-verify-code-3" onclick="getVerifyCode($('#c3').val(), $('#p3').val(), $('#signin-form-err'), $('#get-verify-code-3'))">获取验证码</button>
                    </span>
                    
                           
                           
                    <button class="" >登录</button>
                </form>
                <div class="control-box">
                
                    <span class="bind-account-btn" onclick="show_bind_view()">绑定</span>
                
                </div>
            </div>
            <div id="login-mail-div" style="display: none">
                <div id="login_mail">
                    <form method="post"  class="form signin-form">
                        <div class="u-pr">
                            <select name="country" hidden>
                            </select>
                            <input class="inputng" name="username" type="text" autofocus required
                                   oninvalid="this.setCustomValidity('此字段为必须，请按提示输入')" oninput="setCustomValidity('')" type="text" placeholder="请输入邮箱"/>
                            <div class="error-msg" id="signin-form-err"></div>
                        </div>
                        <input class="inputng" type="password" name="password" type="password" value="" required
                               oninvalid="this.setCustomValidity('此字段为必须，请按提示输入')"
                               oninput="setCustomValidity('')" placeholder="请输入密码"/>
                        <button class="" >登录</button>
                    </form>
                </div>
                <div class="control-box">
                
                    <span class="bind-account-btn" onclick="show_bind_view()">绑定</span>
                
                    <span class="forget_account_btn" onclick="forget_account_btn()">忘记密码</span>
                </div>
            </div>


        </div>
        
        <div class="login-box" id="reset-pwd" style="height: 300px;">
            <div class="fz22 title">修改密码</div>
            <form method="post"  class="form" id="reset-form">
                <div class="u-pr">
                    <input class="inputng" name="oldpasswd" type="password" value="" required
                           oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('密码长度为6-32位，必须是数字，英文或者特殊字符')}"  oninput="setCustomValidity('')" placeholder="请输入旧密码"  pattern="^[ -~]{6,32}$"/>
                    <input class="inputng" name="newpasswd" type="password" value="" required
                           oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('密码长度为6-32位，必须是数字，英文或者特殊字符')}"  oninput="setCustomValidity('')" placeholder="请输入新密码"  pattern="^[ -~]{6,32}$"/>
                    <div class="error-msg" id="reset-form-err"></div>
                </div>
                <button type="submit">修改密码</button>
            </form>
        </div>
        
        <div class="login-box" id="forget-pwd">
            
            <ul class="tabs">
                
                <li><a id="forget-pwd-mail-btn" onclick="showMailForgetPwdView()" class="active">邮件找回</a></li>
            </ul>
            
            
                
                    
                        
                        
                        
                        
                               
                        
                    
                    
                           
                    
                        
                               
                        
                     
                    
                
            
            
            <div id="forget-mail-pwd">
                <form method="post"  class="form" id="forget-mail-form">
                    <div class="u-pr">
                        <input class="inputng" type="text" name="email" required
                               oninvalid="this.setCustomValidity('此字段为必须，请按提示输入')"
                               oninput="setCustomValidity('')"
                               placeholder="请输入邮箱"/>
                        <div class="error-msg" id="forget-mail-form-err"></div>
                    </div>
                    <button type="submit">发送重置连接到邮箱</button>
                </form>
            </div>
            <div class="control-box">
                <span class=""></span>
                <span class="return_login  switch-btn" onclick="switchbtn()"> <i class="ff-icon icon-arrow"></i>返回登录</span>
            </div>
        </div>
        
        <div class="login-box" id="bind_account">
            <ul class="tabs">
                <li><a class="active" id="bind_phone_account_btn" onclick="showPhoneBindView()">绑定手机</a></li>
                <li><a id="bind_mail_account_btn" onclick="showMailBindView()">绑定邮箱</a></li>
            </ul>
            
            <div id="bind_phone">
                <form method="post"  class="form" id="signup-phone-form">
                    <div class="u-pr">
                        <select name="country" id="c1">
                        <option value="86" selected> 中国+86 </option><option value="93" > 阿富汗+93 </option><option value="1890" > 多米尼加共和国+1890 </option><option value="1345" > 开曼群岛+1345 </option><option value="1246" > 巴巴多斯+1246 </option><option value="247" > 阿森松+247 </option><option value="374" > 亚美尼亚+374 </option><option value="1264" > 安圭拉岛+1264 </option><option value="1876" > 牙买加+1876 </option><option value="81" > 日本+81 </option><option value="962" > 约旦+962 </option><option value="7" > 哈萨克斯坦+7 </option><option value="254" > 肯尼亚+254 </option><option value="996" > 吉尔吉斯+996 </option><option value="856" > 老挝+856 </option><option value="371" > 拉脱维亚+371 </option><option value="297" > 阿鲁巴+297 </option><option value="961" > 黎巴嫩+961 </option><option value="266" > 莱索托+266 </option><option value="231" > 利比里亚+231 </option><option value="218" > 利比亚+218 </option><option value="423" > 列支敦士登+423 </option><option value="370" > 立陶宛+370 </option><option value="352" > 卢森堡+352 </option><option value="853" > 澳门+853 </option><option value="389" > 马其顿共和国+389 </option><option value="261" > 马达加斯加+261 </option><option value="61" > 澳大利亚+61 </option><option value="265" > 马拉维+265 </option><option value="60" > 马来西亚+60 </option><option value="960" > 马尔代夫+960 </option><option value="223" > 马里+223 </option><option value="356" > 马耳他+356 </option><option value="222" > 毛里塔尼亚+222 </option><option value="230" > 毛里求斯+230 </option><option value="52" > 墨西哥+52 </option><option value="43" > 奥地利+43 </option><option value="691" > 密克罗尼西亚联邦+691 </option><option value="373" > 摩尔多瓦+373 </option><option value="377" > 摩纳哥+377 </option><option value="976" > 蒙古+976 </option><option value="382" > 黑山共和国+382 </option><option value="212" > 摩洛哥+212 </option><option value="258" > 莫桑比克+258 </option><option value="95" > 缅甸+95 </option><option value="264" > 纳米比亚+264 </option><option value="994" > 阿塞拜疆共和国+994 </option><option value="977" > 尼泊尔+977 </option><option value="31" > 荷兰+31 </option><option value="599" > 荷属安德烈斯群岛+599 </option><option value="687" > 新喀里多尼亚+687 </option><option value="64" > 新西兰+64 </option><option value="505" > 尼加拉瓜+505 </option><option value="227" > 尼日尔+227 </option><option value="234" > 尼日利亚+234 </option><option value="1242" > 巴哈马+1242 </option><option value="47" > 挪威+47 </option><option value="968" > 阿曼+968 </option><option value="680" > 帕劳+680 </option><option value="92" > 巴勒斯坦+92 </option><option value="507" > 巴拿马+507 </option><option value="675" > 巴布亚新几内亚+675 </option><option value="595" > 巴拉圭+595 </option><option value="51" > 秘鲁+51 </option><option value="63" > 菲律宾+63 </option><option value="973" > 巴林+973 </option><option value="48" > 波兰+48 </option><option value="351" > 葡萄牙+351 </option><option value="1787" > 波多黎各+1787 </option><option value="974" > 卡塔尔+974 </option><option value="262" > 留尼旺岛+262 </option><option value="40" > 罗马尼亚+40 </option><option value="7" > 俄罗斯+7 </option><option value="250" > 卢旺达+250 </option><option value="880" > 孟加拉共和国+880 </option><option value="378" > 圣马力诺+378 </option><option value="239" > 圣多美和普林西比+239 </option><option value="966" > 沙特阿拉伯+966 </option><option value="221" > 塞内加尔+221 </option><option value="381" > 塞尔维亚共和国+381 </option><option value="248" > 塞舌尔+248 </option><option value="232" > 塞拉利昂+232 </option><option value="65" > 新加坡+65 </option><option value="421" > 斯洛伐克+421 </option><option value="386" > 斯洛文尼亚+386 </option><option value="252" > 索马里+252 </option><option value="27" > 南非+27 </option><option value="82" > 韩国+82 </option><option value="34" > 西班牙+34 </option><option value="94" > 斯里兰卡+94 </option><option value="211" > 苏丹+211 </option><option value="375" > 白俄罗斯+375 </option><option value="597" > 苏里南+597 </option><option value="268" > 斯威士兰+268 </option><option value="46" > 瑞典+46 </option><option value="41" > 瑞士+41 </option><option value="963" > 叙利亚+963 </option><option value="886" > 台湾+886 </option><option value="992" > 塔吉克斯坦+992 </option><option value="255" > 坦桑尼亚+255 </option><option value="66" > 泰国+66 </option><option value="243" > 刚果民主共和国+243 </option><option value="355" > 阿尔巴尼亚+355 </option><option value="32" > 比利时+32 </option><option value="228" > 多哥+228 </option><option value="676" > 汤加+676 </option><option value="1868" > 特立尼达和多巴哥+1868 </option><option value="216" > 突尼斯+216 </option><option value="90" > 土耳其+90 </option><option value="993" > 土库曼斯坦+993 </option><option value="501" > 伯利兹+501 </option><option value="256" > 乌干达+256 </option><option value="380" > 乌克兰+380 </option><option value="44" > 英国+44 </option><option value="1" > 美国+1 </option><option value="598" > 乌拉圭+598 </option><option value="998" > 乌兹别克斯坦+998 </option><option value="678" > 瓦努阿图+678 </option><option value="58" > 委内瑞拉+58 </option><option value="229" > 贝宁共和国+229 </option><option value="84" > 越南+84 </option><option value="967" > 也门+967 </option><option value="260" > 赞比亚+260 </option><option value="263" > 津巴布韦+263 </option><option value="1441" > 百慕大群岛+1441 </option><option value="975" > 不丹+975 </option><option value="591" > 玻利维亚+591 </option><option value="387" > 波斯尼亚和黑塞哥维那+387 </option><option value="267" > 博茨瓦纳+267 </option><option value="55" > 巴西+55 </option><option value="213" > 阿尔及利亚+213 </option><option value="673" > 文莱+673 </option><option value="359" > 保加利亚+359 </option><option value="226" > 布基纳法索+226 </option><option value="257" > 布隆迪+257 </option><option value="855" > 柬埔寨+855 </option><option value="237" > 喀麦隆+237 </option><option value="1" > 加拿大+1 </option><option value="238" > 佛得角+238 </option><option value="236" > 中非共和国+236 </option><option value="235" > 乍得+235 </option><option value="56" > 智利+56 </option><option value="57" > 哥伦比亚+57 </option><option value="242" > 刚果+242 </option><option value="682" > 库克群岛+682 </option><option value="506" > 哥斯达黎加+506 </option><option value="385" > 克罗地亚+385 </option><option value="376" > 安道尔共和国+376 </option><option value="53" > 古巴+53 </option><option value="357" > 塞浦路斯+357 </option><option value="420" > 捷克共和国+420 </option><option value="45" > 丹麦+45 </option><option value="253" > 吉布提+253 </option><option value="593" > 厄瓜多尔+593 </option><option value="244" > 安哥拉+244 </option><option value="20" > 埃及+20 </option><option value="503" > 萨尔瓦多+503 </option><option value="240" > 赤道几内亚+240 </option><option value="291" > 厄立特里亚+291 </option><option value="372" > 爱沙尼亚+372 </option><option value="251" > 埃塞俄比亚+251 </option><option value="500" > 福克兰群岛+500 </option><option value="298" > 法罗群岛+298 </option><option value="679" > 斐济+679 </option><option value="358" > 芬兰+358 </option><option value="33" > 法国+33 </option><option value="594" > 法属圭亚那+594 </option><option value="689" > 法属波利尼西亚+689 </option><option value="241" > 加蓬+241 </option><option value="220" > 冈比亚+220 </option><option value="995" > 格鲁吉亚+995 </option><option value="49" > 德国+49 </option><option value="233" > 加纳+233 </option><option value="350" > 直布罗陀+350 </option><option value="30" > 希腊+30 </option><option value="1268" > 安提瓜和巴布达+1268 </option><option value="590" > 瓜德罗普岛+590 </option><option value="1671" > 关岛+1671 </option><option value="502" > 危地马拉+502 </option><option value="224" > 巴布亚新几内亚+224 </option><option value="245" > 几内亚比绍共和国+245 </option><option value="592" > 圭亚那+592 </option><option value="509" > 海地+509 </option><option value="504" > 洪都拉斯+504 </option><option value="54" > 阿根廷+54 </option><option value="852" > 香港+852 </option><option value="36" > 匈牙利+36 </option><option value="354" > 冰岛+354 </option><option value="91" > 印度+91 </option><option value="62" > 印度尼西亚+62 </option><option value="98" > 伊朗+98 </option><option value="964" > 伊拉克+964 </option><option value="353" > 爱尔兰+353 </option><option value="972" > 以色列+972 </option><option value="39" > 意大利+39 </option>
                        </select>
                        <input class="inputng number-control" name="phone_number" id="p1" type="text" autofocus required
                               oninvalid="if (value.length < 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('手机格式出错')}" oninput="setCustomValidity('')" type="text" placeholder="请输入手机" />
                        <div class="error-msg" id="form-err-1"></div>
                    </div>
                    
                           
                    <span>
                    <input class="inputng" placeholder='请输入验证码' name="verify_code" type="text" value="" required style="width:210px;"
                           oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('验证码格式出错')}" oninput="setCustomValidity('')" pattern="^[ -~]{4,4}$"/>
                    <button class="get-verify-code" id="get-verify-code-1" onclick="getVerifyCode($('#c1').val(), $('#p1').val(), $('#form-err-1'), $('#get-verify-code-1'))">获取验证码</button>
                </span>
                    <div class="u-pr">
                        <input class="inputng" placeholder='请输入邀请码(选填)' name="referee" type="text"
                               onkeyup="value=value.replace(/[^\w\.\/]/ig,'')" value="" maxlength="8">
                        
                    </div>
                    <button type="submit">绑定</button>
                </form>
            </div>

            
            <div id="bind_mail" style="display: none;">
                <form method="post"  class="form" id="signup-mail-form">
                    <div class="u-pr">
                        <input class="inputng" name="username" type="text" autofocus required
                               oninvalid="if (value.length < 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('邮箱格式出错')}" oninput="setCustomValidity('')" type="text" placeholder="请输入邮箱" pattern="^[A-Za-z0-9\u4e00-\u9fa5]+@[a-zA-Z0-9_-]+(\.[a-zA-Z0-9_-]+)+$"/>
                        <div class="error-msg" id="signup-mail-form-err"></div>
                    </div>
                    <input class="inputng" name="password" type="password" value="" required
                           oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('密码长度为6-32位，必须是数字，英文或者特殊字符')}"  oninput="setCustomValidity('')" placeholder="请输入密码"  pattern="^[ -~]{6,32}$"/>
                    <input class="inputng" placeholder='确认密码' name="password2" type="password" value="" required
                           oninvalid="if (value.length <= 0) {this.setCustomValidity('此字段为必须，请按提示输入')} else {this.setCustomValidity('密码长度为6-32位，必须是数字，英文或者特殊字符')}" oninput="setCustomValidity('')" pattern="^[ -~]{6,32}$"/>
                    <div class="u-pr">
                        <input class="inputng" placeholder='请输入邀请码(选填)' name="referee" type="text"
                               onkeyup="value=value.replace(/[^\w\.\/]/ig,'')" value="" maxlength="8">
                        
                    </div>
                    <button type="submit">绑定</button>
                </form>
            </div>

            <div class="control-box">
                <span></span>
                <span class="return_login switch-btn" onclick="switchbtn()">切换账号</span>
            </div>
        </div>
        
        <div class="invite-panel" id="invite_box" style="background-image: url('./static/sb/dist/img/icon/invite_bk_zh-CN.png') ">
            <div class="close-box-btn" onclick="close_box_btn()"></div>
            
                
            
            <div>
                <ul class="invite-gift-rule">
                    <li>免费版用户每邀请一个好友，即可获得 100 MB高速流量</li>
                    <li>专业版用户每邀请一个好友，即可获得延长 12 小时</li>
                </ul>
                <ul class="invite-gift-rule-tip">
                    <li>（好友绑定手机/邮箱时，输入您的专属邀请码即为成功）</li>
                </ul>
            </div>
            <div>
                <img src=http://localhost:18444/numzl6pm5senx1rs9ikc5vhxkvubjcc2//client/qrcode alt="" style="width: 200px;height: 200px">
                
            </div>
            <div class="invite-qrcode-tips center-cls">
                应用下载地址二维码，可截图保存
            </div>
            <div class="invite-code"><span>邀请码：</span><span>qm98z1nw</span><button class="orange_button" onclick="copy_btn('qm98z1nw')">复制</button></div>
            <div class="invite-url invite-code"><span>下载地址：</span><span>https://ftq.internetedu.online/</span><button class="orange_button"  onclick="copy_btn('https:\/\/ftq.internetedu.online\/')">复制</button></div>
            <div class="invite-copy-onekey">
                <button class="invite-copy-onekey-btn" onclick="copy_btn('免费获取应用《佛跳墙加速器》，高速，安全，无需登录，轻松跳墙。绑定手机或邮箱时，请使用邀请码：qm98z1nw，点击此处下载应用：https:\/\/ftq.internetedu.online\/')"><img src="./static/sb/dist/img/icon/copy_onekey.png" />一键复制</button>
            </div>
        </div>

        
        <div class="getMobileApp-panel" id="getMobileApp_box" style="background-image: url('./static/sb/dist/img/icon/get_moblie_app_bg.png') ">
            <div class="close-box-btn" onclick="close_box_btn()"></div>
        
        
        
            <p class="title">获取佛跳墙手机APP</p>
            <div class="getMobileApp-panel-qrcode">
                <img src=http://localhost:18444/numzl6pm5senx1rs9ikc5vhxkvubjcc2//client/qrcode alt="" style="width: 150px;height: 150px;border-radius:10px;">
            
            </div>
            <div class="getMobileApp-panel-qrcode-tips">
            扫描时请注意，使用支付宝、ＱＱ、微信扫描后，点击右上角<span>【在浏览器打开】</span>下载，否则无法成功下载安装
                <img src="./static/sb/dist/img/icon/share_screenshot.jpg" width="350px" height="500px" class="getMobileApp-Download-FlowImg" style="display: none;"/>
                <img src="./static/sb/dist/img/icon/get_moblie_app_q.png" onmouseover="javascript:showGetMobileAppDownloadFlowImg(true, this);" onmouseout="javascript:showGetMobileAppDownloadFlowImg(false, this);"/>
            </div>
            <div class="getMobileApp-panel-link">
              <a class="getMobileApp-panel-link-tips" href="https://ftq.internetedu.online/" target="_blank">
              https://ftq.internetedu.online/
              </a>
            </div>
            <div class="getMobileApp-panel-desc2">
                <span class="getMobileApp-panel-desc2-tips">
                点击链接进入下载页面，在页面下方，获取佛跳墙最新版本下载地址
                </span>
            </div>

        </div>

        
        <div class="new-version" id="have_update">
            <div class="fz24">立即更新<span class="version_num"></span></div>
            <div class="update-text fz16">
                <p class="version_log"></p>
            </div>
            <a class="update-btn fz16" href="javascript:void(0);" target='_blank'>
                立即更新
            </a>
        </div>
        <div class="new-version" id="no-update">
            <div class="fz24">最新版本 <span class="version_num"></span></div>
            <p class="updated-text fz16">已是最新版本</p>
        </div>
        <div class="user-disabled-box new-version" id="user-disabled-view">
            
            <p class="updated-text fz16">用户账号状态异常</p>
        </div>
        
        <div class="signout-confirm-box" id="signout_confirm">
            <div class="fz24">是否回到游客模式？<span></span></div>
            <div class="signout-text fz16">
                <p></p>
            </div>
            <button class="signout-confirm-btn fz16" id="signout_confirm_btn" onclick="signout()">
            是的
            </button>
        </div>

        
        <div class="paid_notification_cls" id="paid_notification">
            <div class="close-box-btn close-downcount" onclick="close_box_btn($(this))" id="close_btn"></div>
            <div class="center-cls">
                <div class="paid-pic"></div>
            </div>
            <div class="paid_return_box">
                <p class="paid_return_title">恭喜您已成为专业版用户!</p>
                <p class="paid_return_tip"><span class="theme-color">尊敬的专业版用户：</span><br/>您还未绑定账号，请立即绑定您的手机或邮箱，避免因"重装系统"等原因造成账号丢失而影响您的正常使用</p>

                <div class="paid_text">
                    <div class="paid_text_title theme-color">绑定流程：</div>
                    <div>1、点击右上角，打开“个人中心”</div>
                    <div>2、点击“绑定手机/邮箱”，选择绑定方式</div>
                    <div>3、填写相关信息，完成绑定</div>
                </div>
                <div class="center-cls">
                    <button class="bind_later disable-btn close-downcount" onclick="close_box_btn($(this));">暂不绑定</button>
                    <button class="bind_account_now green-btn" onclick="close_box_btn($(this));show_bind_view();" >立即绑定</button>
                </div>
            </div>
        </div>

        
        <div class="free-version-cannot-change-line-cls" id="free-version-cannot-change-line">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="free-change-line-title">温馨提示</div>
            <p class="free-version-change-line-tip">您好，免费版线路为固定线路，无法智能切换，请升级专业版后再自由选择线路。</p>
        </div>
        
        <div class="report-problem-box" id="report_problem_view">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="report-problem-title">问题反馈</div>
            <form method="post"  class="report-problem-form-cls" id="report-problem-form">
                <table class="report-problem-table">
                    <tr>
                        <td>问题反馈</td>
                        <td>
                            <select name="problem_type" id="problem_type">
                                
                            </select>
                        </td>
                    </tr>
                    <tr>
                        <td>手机号码</td>
                        <td>
                            <input class="inputng number-control" name="user_mail" type="number" maxlength="15" value=""
                                   required oninvalid="this.setCustomValidity('此字段为必须，请按提示输入')" oninput="setCustomValidity('')" />
                        </td>
                    </tr>
                    <tr>
                        <td>问题描述</td>
                        <td>
                            <textarea rows="8" cols="20" style="resize:none;" name="problem_description" required maxlength="500" onKeyDown='if (this.value.length>=500){event.returnValue=false}'></textarea>
                        </td>
                    </tr>
                    <tr>
                        <td></td>
                        <td><button class="green-btn" id="submit-problem-report">提交</button></td>
                    </tr>
                </table>

            </form>
        </div>
        
        <div class="anti-lost-box" id="anti_lost_view">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="center-cls">
                <img src="./static/sb/dist/img/icon/info.png" />
            </div>
            <div class="anti-lost-box-title">客户端出现无法修复的错误，请下载最新版本。</div>
            <div class="center-cls">
                <a class="green-btn padding-lr-40 a2btn" target="_blank" href="https://ftq.internetedu.online/">下载最新版本</a>
            </div>
        </div>
        
        <div class="reporting-problem-box" id="reporting_problem_view">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="report-success">
                <div class="center-cls">
                    <img src="./static/sb/dist/img/icon/ok.png" />
                </div>
                <div class="center-cls">
                    <div class="report-success-title">提交完成!</div>
                </div>
                <div class="progress-div">
                    <div class="progress-bar">
                        <div class="progress">
                        </div>
                    </div>
                    <div class="progress-value">20%</div>
                </div>
            </div>
            <div class="report-overtime-failed">
                <div class="center-cls">
                    <img src="./static/sb/dist/img/icon/overtime.png" />
                </div>
                <div class="center-cls">
                    <div class="report-overtime-title">响应超时，提交失败!</div>
                </div>
                <div class="center-cls">
                    <button class="green-btn padding-lr-40" onclick="show_report_problem_view()">返回重新提交</button>
                </div>
            </div>
            <div class="report-processing">
                <div class="center-cls">
                    <img src="./static/sb/dist/img/icon/reporting.png" />
                </div>
                <div class="center-cls">
                    <div class="report-processing-title">问题提交中...</div>
                </div>
                <div class="progress-div">
                    <div class="progress-bar">
                        <div class="progress">
                        </div>
                    </div>
                    <div class="progress-value">20%</div>
                </div>
            </div>
        </div>
        
        <div class="user-over-limit-cls" id="user-over-limit">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="pac-tips-title-cls center-cls">温馨提示</div>
            <p class="user-over-limit-descp">您好，您的账户登录了3个设备，无法再登录新的设备，如果您想登录新的设备，可以选择：</p>
            <div class="center-cls">
                <button class="logout-all-device disable-btn" onclick="logout_all_device()">注销已登录设备</button>
                <button class="logout-other-account green-btn" onclick='(function(){toggleAlertBox($("#login"));})();'>登录其他账户</button>
            </div>
        </div>
        
        <div class="logout-all-device-success" id="logout-all-device-success">
            <div class="close-box-btn" onclick="close_box_btn()" id="close_btn"></div>
            <div class="pac-tips-title-cls center-cls">温馨提示</div>
            <p class="user-over-limit-logout-success-descp">已经注销当前账户已登录的设备，可以登录新的设备了</p>
            <div class="center-cls">
                <button class="login-cur-device green-btn" onclick='signin(curUserInfo);'>登录当前设备</button>
            </div>
        </div>
    </div>
</div>


<div class="msg-wrap" id="five-wrap">
    <div class="mask" id="closeMsg-5" onclick="closeMsg5();">
        
        <div class="pac-pane-cls" id="pac-pane">
            <div class="close-box-btn" onclick="close_box_btn_5()" id="close_btn"></div>
            <div class="pac-tips-title-cls center-cls">温馨提示</div>
            <div class="pac-tips-cls">设置代理环境失败，请确定能够上网，如果不行，请检查环境，再重新连接。</div>
            <div class="pac-tips-cls aligin-right-cls"><a href="https://gsoogsdafsle.github.io/wizard/proxy_settings.html" target="_blank">详细教程</a></div>
        </div>
    </div>
</div>


<div class="msg-wrap" id="fourth-wrap">
    <div class="mask" id="closeMsg-4" onclick="closeMsg4();">
        <div class="pro-package renew-pane-cls" id="renew-pane">
            <div class="close-box-btn" onclick="close_box_btn_4()"></div>
            <div class="gift-pic"></div>
            <div class="free-title"><span>重要提示：</span>亲爱的用户，您的专业版即将到期，到期后网速将变为1KB/S，非常缓慢、卡顿，严重影响您的翻墙体验，建议您立即续费专业版</div>
            <div class="btn-item center-cls">
                <button class="upgrade-btn renew-upgrade-btn update_btn">立即续费</button>
            </div>
            <div >
                <div class="free-box-upgrade">
                    <div class="free-title-upgrade center-cls">免费版</div>
                    <table>
                        <tr>
                            <td>网速</td>
                            <td>1KB/S</td>
                        </tr>
                        <tr>
                            <td>线路</td>
                            <td>随机</td>
                        </tr>
                        <tr>
                            <td>稳定性</td>
                            <td>不保障</td>
                        </tr>
                        <tr>
                            <td>高速流量</td>
                            <td>100MB体验</td>
                        </tr>
                        <tr>
                            <td>安全私密性</td>
                            <td>不保障</td>
                        </tr>
                        <tr>
                            <td>广告</td>
                            <td>有</td>
                        </tr>
                        <tr>
                            <td>服务</td>
                            <td>无</td>
                        </tr>
                        <tr>
                            <td>特权</td>
                            <td>无</td>
                        </tr>
                    </table>
                </div>

                <div class="pro-box-upgrade">
                    <div class="pro-title-upgrade center-cls">专业版</div>
                    <table>
                        <tr>
                            <td>网速</td>
                            <td>5000KB/S</td>
                        </tr>
                        <tr>
                            <td>线路</td>
                            <td>VIP专属线路</td>
                        </tr>
                        <tr>
                            <td>稳定性</td>
                            <td>100%稳定</td>
                        </tr>
                        <tr>
                            <td>高速流量</td>
                            <td>无限流量</td>
                        </tr>
                        <tr>
                            <td>安全私密性</td>
                            <td>100%安全</td>
                        </tr>
                        <tr>
                            <td>广告</td>
                            <td>无</td>
                        </tr>
                        <tr>
                            <td>服务</td>
                            <td>VIP专属客服</td>
                        </tr>
                        <tr>
                            <td>特权</td>
                            <td>续费折上折</td>
                        </tr>
                    </table>
                </div>
                <div class="upgrade-arrow"></div>
            </div>
        </div>
    </div>
</div>

<div class="msg-wrap" id="second-wrap">
    <div class="mask" id="closeMsg-2" onclick="closeMsg2();">
        
        <div class="notice-pane-cls" id="notice-pane">
            <div class="close-box-btn" onclick="close_box_btn_2()" id="close_btn"></div>
            <div class="notice-pane-title">系统公告</div>
            <div class="notice-pane-content">
            </div>
        </div>
    </div>
</div>


<div class="msg-wrap" id="third-wrap">
    <div class="mask" id="closeMsg-3" onclick="closeMsg3();">
        
        <div class="ie-pane-cls" id="ie-pane">
            <div class="close-box-btn" onclick="close_box_btn_3()" id="close_btn"></div>
            <div class="ie-tips-cls">您当前使用的浏览器可能会影响您的体验，请下载Chrome浏览器，并设置为默认浏览器</div>
            <div class="download-cls-container">
                
                <a href="https://chrome.en.softonic.com/" target="_blank" class="download-cls">Chrome下载</a>
            </div>

        </div>
    </div>
</div>

<script>
    function getEvent(){
        return window.event || arguments.callee.caller.arguments[0];
    }
    function close_box_btn(btn) {
        if (btn && btn.hasClass("close_waiting_downcount")) {
            return
        }
        clearInterval(timer)
        $('#first-wrap').hide();
        $("#closeMsg>div").hide();
        notifyUserClose(LastToggleAlertBox);
        LastToggleAlertBox = null;
    }

    function close_box_btn_2() {
        $('#second-wrap').hide();
        $("#closeMsg-2>div").hide();
        notifyUserClose(LastToggleAlertBox2);
        LastToggleAlertBox2 = null;
    }

    function close_box_btn_3() {
        $('#third-wrap').hide();
        $("#closeMsg-3>div").hide();
    }

    function close_box_btn_4() {
        $('#fourth-wrap').hide();
        $("#closeMsg-4>div").hide();
        notifyUserClose(LastToggleAlertBox4);
    }

    function close_box_btn_5() {
        $('#five-wrap').hide();
        $("#closeMsg-5>div").hide();
        notifyUserClose(LastToggleAlertBox5);
    }

    
    
    
    
    
    
    
    
    (function(){

    })()
</script>

    </nav>


<div id="page-wrapper" class="map-bg connect-panel">

    <div class="free-version" id="free-version" style="display: none">
        <div class="version-box">
            <img src="./static/sb/dist/img/icon/connect_free_zh.png" class="update_btn" style="width:690px;height:110px;" alt="" >
            <div>
                <span class="free-version_text">
                    <div>剩余高速流量:  <span class="account_free_flows">0</span></div>
                    <button class="update_btn">立即升级</button>
                </span>
            </div>
        </div>
        <div class="free-version-tips3"></div>
    </div>

    <div class="pro-version" id="pro-version" style="display: none">
        <div class="version-box">
            <div class="left-box">
                <img src="./static/sb/dist/img/icon/major.png" style="width:78px;height:78px;"  alt="" onclick="">
                <div class="tips-box">
                    <div class="tips1">尊敬的专业版用户</div>
                    <div class="tips2" style="display: none">专业版即将到期，现在续费有优惠！<button class="upgrade-btn update_btn">立即续费</button></div>
                </div>
            </div>
            <div>
                <span class="pro-version_text">
                    <div>专业版剩余时间: <span><span class="account_day"></span>天<span class="account_hour"></span>小时<span class="account_min"></span>分钟</span></div>
                </span>
            </div>
        </div>
        <div class="pro-tips">您尚未绑定手机/邮箱，绑定后可同时在3个设备上使用<span class="bind_btn">立即绑定</span></div>
    </div>

    <div class="bind-pro-version" id="bind-pro-version" style="display: none">
        <div class="version-box">
            <div class="left-box">
                <img src="./static/sb/dist/img/icon/major.png" style="width:78px;height:78px;"  alt="" onclick="">
                <div class="tips-box">
                    <div class="tips1">尊敬的专业版用户</div>
                    <div class="tips2" style="display: none;">专业版即将到期，现在续费有优惠！<button class="upgrade-btn update_btn">立即续费</button></div>
                </div>
            </div>
            <div>
                <span class="pro-version_text">
                    <div>专业版剩余时间: <span><span class="account_day"></span>天<span class="account_hour"></span>小时<span class="account_min"></span>分钟</span></div>
                </span>
            </div>
        </div>
    </div>

    <div id="gka" class="connect-noconnect" onclick="toggle_connect()">
        <div>
            <div class="connect-tips-1" >
                
            </div>
            <p class="connect-time center-cls">
                <span class="connect-time-tip"></span>
                <span class="connect-time-str"></span>
            </p>
            <div class="connect-tips-2 center-cls">
                
            </div>
        </div>
    </div>
    <div class="center-cls connect-tips-3 bold-font" style="display: none;" id="connect-info-free-tip">
        <p>
            <span class="icon-lamp"></span><span>您正在使用</span><span class="theme-color">免费版，网速缓慢存在掉线风险，</span><span>建议您</span><span class="theme-color">立刻升级</span><span>专业版!</span>
        </p>
    </div>
    <div class="center-cls connect-tips-3 bold-font" style="display: none;" id="connect-info-pro-tip">
        <p>
        <span class="icon-lamp"></span><span>您的专业版剩余时间:</span><span class="theme-color"><span class="account_day"></span>天<span class="account_hour"></span>小时<span class="account_min"></span>分钟</span>
            <span class="connect-pro-renew">，为了您的体验，请</span>
            <span class="theme-color connect-pro-renew">及时续费!</span>
        </p>
    </div>
    <div class="connect-box">
        <div class="connect-title connect_info">
            <div>连接状态</div>
            <div></div>
            
            <div>当前最优线路</div>
        </div>
        <div class="connect-row connect_info ">
            <div class="fail status-points" class="connect-col">
                <i></i>
                <p class="status-text">
                    
                </p>

            </div>
            <div></div>
            
            <div class="location" id="location1">
                <span id="flag" class="flag-icon flag-icon-"></span>
                <span id="country">USA</span>
                <span>
                    <a class="connect-switch" onclick="switchServer()">切换</a>
                </span>
            </div>
        </div>
    </div>
    <div class="center-cls fz14" style="display: none" id="connect-info-free">
        <p>
        登入方式:<span class="btn-common-color">免费版</span><span class="theme-color">（限速 1 KB/S） </span><button class="upgrade-btn renew-upgrade-btn-connect-info update_btn">立即升级</button>
        </p>
    </div>
    <div class="center-cls fz14" style="display: none" id="connect-info-pro">
        <p>
        登入方式:<span class="btn-common-color">专业版</span><span class="theme-color">（无限高速流量）</span>
            <button class="upgrade-btn renew-upgrade-btn-connect-info update_btn connect-pro-renew">立即续费</button>
        </p>
    </div>
</div>


</div>



<script src="static/sb/vendor/jquery/jquery.min.js"></script>


<script src="static/sb/vendor/bootstrap/js/bootstrap.min.js"></script>


<script src="static/sb/vendor/metisMenu/metisMenu.min.js"></script>


<script src="static/sb/dist/js/sb-admin-2.min.js"></script>


<script src="static/js/common.js"></script>




<script>
    var clientStatus = 9;
    var refreshTimer = null;
    var refreshInfoTimer = null;

    refreshInfoTimer = setInterval(function(){
        changeStatus()
    }, 3000);

    function getParam(name){
        var reg = new RegExp("(^|&)" + name + "=([^&]*)(&|$)");
        var result = window.location.search.substr(1).match(reg);
        if (result != null) {
            return decodeURIComponent(result[2]);
        } else {
            return null;
        }
    }
    function toggleAlertBox(boxId, e) {
        if (e) {
            e.preventDefault();
        }
        $("#closeMsg>div").hide();
        $("#first-wrap").show();
        boxId.show();
    }
    $(function () {
        $("#bind-pro-version").hide();
        $("#free-version").hide();
        $("#pro-version").hide();
        changeStatus();

        $(".update_btn").on('click', function(e){
            getPlans(); 
            if (! true ) {
                toggleAlertBox($("#login"), e)
            } else {
                toggleAlertBox($("#update"), e);
            }
        })
        $(".bind_btn").on('click',function(e) {
            toggleAlertBox($("#bind_account"), e)
        })
        
        
        
        
    });
    if (getParam('refresh')>0) {
        var refresh = getParam('refresh');
        alert("付费状态确认可以需要1-2分钟，请稍后查看VPN的状态。")
        clearTimeout(refreshTimer);
        refreshTimer = setTimeout(function(){
            window.location = window.location.origin + window.location.pathname;
            clearTimeout(refreshTimer);
        }, refresh * 1000)
    }
    
    function changeStatus() {
        getInfos();
        
        
        
        getUserName();
        $.ajax({
            method: "POST",
            url: "client/info",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                if (data.data) {
                    clientStatus = data.data.clientStatus;
                    if (clientStatus == 2) {
                        return
                    }
                    
                    
                    
                    
                    connectedTime = data.data.connected_time;

                    statusStyle(clientStatus, connectedTime);
                    $("#location1").hide();
                    $("#location2").hide();
                    $('#flag').attr('class', 'flag-icon flag-icon-' + data.data.icon)
                    if (clientStatus == 1) {
                        $("#location1").show();
                        $('#country').text(data.data.location)
                        $('.speed').text(data.data.speed)
                        $('.connect_info').show()
                    } else if (clientStatus == -1) {
                        $("#location2").show();
                        $('.connect_info').show()
                        $("#location2").text("智能算法为您自动选择")
                    } else {
                        $('.connect_info').show()
                        $("#location2").show();
                        $("#location2").text("智能算法为您自动选择")
                    }
                }
                
                
                
            },
        });
    }
    function getUserName() {
        $.ajax({
            method: "POST",
            url: "account/username",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                if (data.code == 0){
                    $("#account").text(data.username)
                }
            },
        });
    }
    function getLocalItem (name) {
        var val = localStorage.getItem(name)
        try {
            return JSON.parse(val)
        } catch (e) {
            return val
        }
    }
    function statusStyle(clientStatus, connectedTime) {
        var status = {
            '0': {
                text: '加载中',
                tips_1 : '连接中',
                tips_2 : '',
                point_class: 'fail',
                connect_box: 'connect-connectting',
                connect_time_tip : '',
                connect_time_str : ''
            },
            '1': {
                text: '连接成功',
                tips_1 : '连接成功',
                tips_2 : '点击图标，断开连接',
                point_class: 'success',
                connect_box: 'connect-success',
                connect_time_tip : "已连接时长:",
                connect_time_str : connectedTime
            },
            '-1': {
                text: '未连接',
                tips_1 : '已断开',
                tips_2 : '点击图标，再次连接',
                point_class: 'fail',
                connect_box: 'connect-noconnect',
                connect_time_tip : "本次连接时长:",
                connect_time_str : connectedTime
            },
        };

        if(clientStatus == -1 || clientStatus == 0) {
            $('.tip_toogle').hide();
        } else {
            $('.tip_toogle').show();
        }
        $(".status-points").attr('class', 'status-points '+status[clientStatus].point_class);
        $(".speed").attr('class', 'speed '+status[clientStatus].point_class)
        $(".status-text").text(status[clientStatus].text);
        $('#gka').attr('class', status[clientStatus].connect_box);
        
        $('.connect-tips-1').text(status[clientStatus].tips_1);
        
        $('.connect-tips-2').text(status[clientStatus].tips_2);
        $('.connect-time-tip').text(status[clientStatus].connect_time_tip)
        $('.connect-time-str').text(status[clientStatus].connect_time_str);
        
    }

    function toggle_connect(e) {
        if (clientStatus == 1) {
            disconnect()
        }
        else if (clientStatus == -1) {
            connect()
        }
    }
    function connect(e) {
        if (clientStatus == -1) {
            $.ajax({
                method: "POST",
                url: "client/connect",
                contentType: "application/json; charset=utf-8",
                success: function(data) {
                    if (!data) return
                    if (data.code == 0) {
                        
                        changeStatus()
                        
                        
                        
                    } else {
                        alert(data.msg)
                    }

                },
            });
        }
    }
    function disconnect(e) {
        if (clientStatus == 1) {
            $.ajax({
                method: "POST",
                url: "client/disconnect",
                contentType: "application/json; charset=utf-8",
                success: function(data) {
                    if (!data) return

                    if (data.code == 0) {
                        
                        changeStatus()
                        
                        
                        
                    } else {
                        alert(data.msg)
                    }
                },
            });
        }
    }
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
</script>



</body>

<script>

    
    function IEVersion() {
        var userAgent = navigator.userAgent; 
        var isIE = userAgent.indexOf("compatible") > -1 && userAgent.indexOf("MSIE") > -1; 
        var isEdge = userAgent.indexOf("Edge") > -1 && !isIE; 
        var isIE11 = userAgent.indexOf('Trident') > -1 && userAgent.indexOf("rv:11.0") > -1;
        if(isIE) {
            var reIE = new RegExp("MSIE (\\d+\\.\\d+);");
            reIE.test(userAgent);
            var fIEVersion = parseFloat(RegExp["$1"]);
            if(fIEVersion == 7) {
                return 7;
            } else if(fIEVersion == 8) {
                return 8;
            } else if(fIEVersion == 9) {
                return 9;
            } else if(fIEVersion == 10) {
                return 10;
            } else {
                return 6;
            }
        } else if(isEdge) {
            return 'edge';
        } else if(isIE11) {
            return 11; 
        }else{
            return -1;
        }
    }

    function ShowIETips() {
        var ie_version = IEVersion();
        if (ie_version != -1 && ie_version < 11){
            toggleAlertBox3("#ie-pane")
        }
    }

    ShowIETips();
    var timer = null;
    function getEvent(){
        return window.event || arguments.callee.caller.arguments[0];
    }
    function getExpDay() {
        $.ajax({
            method: "POST",
            url: "expiration",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                $(".account_day").text(data.data.account_day)
                $(".account_hour").text(data.data.account_hour)
                $(".account_min").text(data.data.account_min)
                alert(data.data.user_free_flow)
                $(".account_free_flows").text((data.data.user_free_flow/(1024*1024)).toFixed(0) + 'MB')

                if (data.data.account_day <  10 ) {
                    $(".tips2").show()
                } else {
                    $(".tips2").hide()
                }
            
            
            
            
                
                
                
                
                
                
                
                
            },
        });
    }

    function getDiviceList() {
        var item = {};
        $.ajax({
            method: "POST",
            url: "device/list",
            contentType: "application/json; charset=utf-8",
            success: function (data) {
                var list = data.data;
                for (var i in list) {
                    var device = list[i];
                    item[i] = device;

                    device_html = '<div class="equipment-item equip'+ i +'">';

                    if (device.isCurrent) {
                        device_html += '<span>'+ device.name + ' ' + "(当前设备)" + '</span>'
                    } else {
                        device_html += '<span>'+ device.name +'</span>' +
                                '<span class="device-out device'+ i +'">注销</span>'
                    }
                    device_html += '</div>'
                    $(".equipment-list").append(device_html)
                }
                $(".device-out").click(function(){
                    var currentIndex = -1;
                    for (var i in list) {
                        if($(this).hasClass('device'+i)) {
                            currentIndex = i;
                            if (list[currentIndex].isCurrent) {
                                $.ajax({
                                    method: "POST",
                                    url: "device/logout",
                                    contentType: "application/json; charset=utf-8",
                                    data: JSON.stringify({
                                        name: list[currentIndex].name,
                                        cookie: list[currentIndex].cookie
                                    }),
                                    success: function(data) {
                                        location.reload()
                                    }
                                });
                            } else {
                                $.ajax({
                                    method: "POST",
                                    url: "device/logout",
                                    contentType: "application/json; charset=utf-8",
                                    data: JSON.stringify({
                                        name: list[currentIndex].name,
                                        cookie: list[currentIndex].cookie
                                    }),
                                    success: function(data) {
                                        $(".equip"+currentIndex).remove();
                                    }
                                });
                            }

                        }
                    }
                })
            },
        });
    }
    function setLang(){
        var lang = getLocalItem('lang') ? getLocalItem('lang') : ('en-US' == window.navigator.language || 'zh-CN' == window.navigator.language) ? window.navigator.language : 'zh-CN';
        if (!getLocalItem('lang')) {
            $.ajax({
                url: 'setlang',
                type: 'POST',
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify({"locale": lang, "init": true}),
                success: function() {
                    location.reload(true)
                    setLocalItem('lang', lang);
                },
            });
        }
    }

    var showed_user_disabled_view = false;

    function getInfos() {
        $.ajax({
            method: "POST",
            url: "account/info",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                if (data.code == 0) {
                    isVip = data.data.is_vip;
                    isSpeedLimit = data.data.speed_limit;
                    UserFreeFlow = data.data.user_free_flow;
                    need_show_tips = data.data.need_show_tips;
                    show_user_disable_tips = !data.data.is_enabled;
                    is_paid = data.data.is_paid;
                    show_paid_tip = data.data.show_paid_tip;
                    need_refresh = data.data.need_refresh;
                    need_show_pac = data.data.show_pac;
                    has_popup_renew_box = data.data.has_popup_renew_box;


                    if (need_refresh) {
                        location.reload();
                        return
                    }

                    if (need_show_pac && !$('#pac-pane').isVisible) {
                        toggleAlertBox5($("#pac-pane"));
                    }

                    $(".account_day").text(data.data.account_day)
                    $(".account_hour").text(data.data.account_hour)
                    $(".account_min").text(data.data.account_min)
                    $(".account_free_flows").text((UserFreeFlow/(1024*1024)).toFixed(0) + 'MB')

                    if (data.data.account_day <  10 ) {
                        $(".tips2").show();
                        $(".connect-pro-renew").show();
                        if ((!has_popup_renew_box) && isVip && !$("#renew-pane").isVisible &&
                                (data.data.account_day > 0 || data.data.account_hour > 0 || data.data.account_min > 0)) {
                            toggleAlertBox4($("#renew-pane"))
                        }
                    } else {
                        $(".tips2").hide();
                        $(".connect-pro-renew").hide();
                    }

                    $('.end_date').text(data.data.end_date);

                    if (data.data.is_enabled) {
                        if (isVip) {
                            $('.account_type').text('专业版');
                            $('.account_date').text('专业版结束日期');
                            $(".update_pro_text_cls").text('续费专业版');
                            $("#invite_fd_text").text('邀请好友');

                            if (  true  ) {
                                $("#pro-version").show()
                                $("#bind-pro-version").hide();
                                $("#free-version").hide();
                            } else {
                                $("#bind-pro-version").show()
                                $("#free-version").hide();
                                $("#pro-version").hide();
                            }

                            $("#connect-info-pro").show();
                            $("#connect-info-pro-tip").show();
                            $("#connect-info-free").hide();
                            $("#connect-info-free-tip").hide();
                            
                            
                            
                            
                        } else {
                            $('.account_type').text('免费版');
                            $('.account_date').text('专业版结束日期');
                            $(".update_pro_text_cls").text('升级至专业版');
                            $("#invite_fd_text").text('邀请好友');
                            $("#free-version").show();
                            $("#bind-pro-version").hide();
                            $("#pro-version").hide();
                            $("#connect-info-pro").hide();
                            $("#connect-info-pro-tip").hide();
                            $("#connect-info-free").show();
                            $("#connect-info-free-tip").show();
                            
                            if (need_show_tips && !is_paid && getLocalItem("lang")){ 
                                toggleAlertBox($("#pro-package"));
                                showedUpgradeTips();
                                
                                
                                
                            }
                            else if (!is_paid) {
                                
                                if (UserFreeFlow > 0) {
                                    $(".free-version-tips3").text('温馨提示：您目前使用的是免费版，尚有部分免费高速流量，升级至专业版可以获得比免费版快20倍的上网速度和100%稳定的VIP专用线路');
                                } else {
                                    $(".free-version-tips3").text('温馨提示：您目前使用的是免费版，上网速度只能达到专业版的5%，我们也不保障免费版的稳定性，请升级到专业版可以获得比免费版快20倍的上网速度和100%稳定的VIP专用线路');
                                }
                            }
                            else {
                                
                                
                            }
                        }

                    } else {
                        if ($("#user-disabled-view").is(":hidden") && !showed_user_disabled_view) {
                            toggleAlertBox($("#user-disabled-view"));
                            showed_user_disabled_view = true;
                        }
                    }
                }
                
                if (show_paid_tip && ($("#paid_notification").is(":hidden"))) {
                    if (is_paid) {
                        $(".paid_return_title").text('恭喜您已成为专业版用户!');
                    } else {
                        $(".paid_return_title").text('温馨提示');
                    }
                    showPaidNotificationView();
                }
                
            },
        });
    }

    function getUserName() {
        $.ajax({
            method: "POST",
            url: "account/username",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                if (data.code == 0){
                    $("#account").text(data.username)
                }
            },
        });
    }

    function showedUpgradeTips() {
        $.ajax({
            method: "POST",
            url: "client/showed/upgrade_tip",
            contentType: "application/json; charset=utf-8",
            success: function(data) {

            },
        })
    }
    
    
    
    
    
    
    
    
    
    
    
    var isSignOutDone = true;
    function signout() {
        if (!isSignOutDone) {
            return
        }
        isSignOutDone = false;
        $.ajax({
            method: "POST",
            url: "account/signout",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                
                if (data.code == 0) {
                    location.reload();
                    isSignOutDone = true;
                }
            },
        });
    }
    
    function switchServer() {
        $.ajax({
            method: "POST",
            url: "server/switch",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                if (data.code == 0) {
                    location.reload();
                } else if (data.code == 1){
                    toggleAlertBox($("#free-version-cannot-change-line"))
                } else {
                    alert(data.msg);
                }
            },
        });
    }
    var verifycode_timer = null;

    function getVerifyCode(country, phone_number, err_ele, verify_code_ele) {
        
        if (verifycode_timer == null){
            if (!phone_number) {
                err_ele.text("请输入手机号码");
                err_ele.show();
                return
            }
            err_ele.hide()
            verify_code_ele.attr("disabled", true);

            
            $.ajax({
                method: "POST",
                url: "account/signup/verifycode",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify({"country" : country, "phone_number" : phone_number}),
                success: function(data) {
                    if (data.code == 0) {
                        var downcnt = 60;
                        verifycode_timer = setInterval(function () {
                            downcnt --;
                            if (downcnt <= 0){
                                verify_code_ele.text("获取验证码");
                                verify_code_ele.attr("disabled", false);
                                clearInterval(verifycode_timer)
                                verifycode_timer = null
                                return
                            }
                            downcnt > 9 ?  verify_code_ele.text(downcnt + "s") :  verify_code_ele.text("0" + downcnt + "s")
                        }, 1000);
                        verify_code_ele.text(downcnt + "s");
                        if (data.msg) {
                            err_ele.addClass("theme-color");
                            err_ele.text(data.msg);
                            err_ele.show();
                            
                            
                        }
                    } else {
                        err_ele.removeClass("theme-color")
                        err_ele.text(data.msg);
                        err_ele.show();
                        verify_code_ele.attr("disabled", false);
                    }
                },
            });
        }
    }

    
    function accountBox (){
        if ($('#account>i').hasClass("u-recovery")) {
            $('#account>i').removeClass("u-recovery").addClass('u-flip');
            $('.base-account').show();
        } else {
            $('#account>i').removeClass("u-flip").addClass('u-recovery');
            $('.base-account').hide();
        }
    }
    function copyBtn() {
        var Url2=$('.url').html();
        var oInput = document.createElement('input');
        oInput.value = Url2;
        document.body.appendChild(oInput);
        oInput.select(); 
        document.execCommand("Copy"); 
        oInput.className = 'oInput';
        oInput.style.display='none';
        Toast("复制完成", 2000);
    }
    function resetpasswd(e) {
        e = getEvent()
        toggleAlertBox($("#reset-pwd"), e)
    }
    function invite_fd(e) {
        e = getEvent()
        toggleAlertBox($("#invite_box"), e);

        $.ajax({
            method: "POST",
            url: "client/action/share",
            contentType: "application/json;charset=utf-8",
            success: function(data) {}
        });
    }
    
    function getMobileApp_fd(e) {
        e = getEvent()
        toggleAlertBox($("#getMobileApp_box"), e);
    }

    function check_update(e){
        e = getEvent()
        getVersion(e);
    }

    function show_notice(e) {
        e = getEvent();
        e.preventDefault()
        getNotices();
        toggleAlertBox2($("#notice-pane"),e)
    }

    var is_reporting = false;
    

    $("#report-problem-form").submit(function(e) {
        e.preventDefault();
        if (is_reporting) {
            return false;
        }
        is_reporting = true;

        var browserInfo = getBrowserInfo();
        var form_data = $(this).serializeObject();
        form_data["problem_description"] = form_data["problem_description"].trim();
        form_data["problem_type"] = form_data["problem_type"].trim();
        form_data["user_mail"] = form_data["user_mail"].trim();


        if (form_data["problem_type"].length == 0) {
            getProblemType();
            is_reporting = false;
            return
        }

        if (form_data["problem_description"].length < 3) {
            Toast("描述的越清晰，越能帮您解决问题哦", 3000)
            is_reporting = false;
            return;
        }
        form_data["browser_info"] = browserInfo.browser + " " + browserInfo.browserVersion;
        $("#submit-problem-report").attr("disabled", true);

        $.ajax({
            method: "POST",
            url: "problem_report",
            contentType: "application/json; charset=utf-8",
            data: JSON.stringify(form_data),
            success: function(data) {
                
                $("#first-wrap").hide();
                if (data.code == 0) {
                    
                    ProgressBar($(".progress"), $(".progress-value"), 1000, getReportProblemProgress);
                    showReportProcessing();
                } else {
                    
                }
            },
        });
    });

    
    function showAntiLostError() {
        var e = getEvent()
        toggleAlertBox($("#anti_lost_view"), e)
    }

    
    function showResponseError() {
        var e = getEvent()
        $(".report-success").hide();
        $(".report-processing").hide();
        $(".report-overtime-failed").show();
        toggleAlertBox($("#reporting_problem_view"),e)
    }

    
    function showGetMobileAppDownloadFlowImg(visible, pointer) {
        var imgObj = $(".getMobileApp-Download-FlowImg");
        var leftPos = pointer.offsetLeft - imgObj[0].width - 20;
        var topPos = pointer.offsetTop - imgObj[0].height + 35;
        imgObj.css("left", leftPos + "px");
        imgObj.css("top", topPos + "px");

        if (visible) {
            imgObj.show();
        } else {
            imgObj.hide();
        }
    }
    
    function showReportProcessing() {
        var e = getEvent()
        $(".report-success").hide();
        $(".report-overtime-failed").hide();
        $(".report-processing").show();
        toggleAlertBox($("#reporting_problem_view"),e)
    }

    
    function showReportSuccess() {
        var e = getEvent()
        $(".report-processing").hide();
        $(".report-overtime-failed").hide();
        $(".report-success").show();
        toggleAlertBox($("#reporting_problem_view"),e)

        setTimeout(function(){
            if (!$(".report-success").is(":hidden")){
                close_box_btn();
            }
        },2000)
    }

    function getReportProblemProgress(progress, callback) {
        $.ajax({
            method: "POST",
            url: "problem_report/progress",
            contentType: "application/json;charset=utf-8",
            success: function(data) {
                if (data.code == 0) {
                    status = data.data.status;
                    status_info = data.data.status_info;
                    progress = data.data.progress;

                    if (status < 2) {
                        callback(0,false);
                    } else if (status == 2){
                        callback(progress,false)
                    } else {
                        callback(100,true);
                    }
                    if (status == 6) {
                        showReportSuccess();
                        is_reporting = false;
                        $("#submit-problem-report").attr("disabled", false);
                        $("#report-problem-form input").val("");
                        $("#report-problem-form textarea").val("");
                    } else if (status > 3){
                        showResponseError();
                        is_reporting = false;
                        $("#submit-problem-report").attr("disabled", false);
                    }
                }
            }
        })
    }
    function getVersion(e) {
        var verStatus = {
            2: '更新失败',
            3: '更新中'
        }
        $.ajax({
            method: "POST",
            url: "client/ver",
            contentType: "application/json; charset=utf-8",
            success: function(data) {
                var verInfo = JSON.parse(data);
                $(".version_num").text(verInfo.ver)
                if (verInfo.status == 0) {
                    clearInterval(timer);
                    toggleAlertBox($("#no-update"), e);
                } else {
                    toggleAlertBox($("#have_update"), e);
                    clearInterval(timer);
                    timer = setInterval(function(){
                        getVersion(e)
                    }, 1000)
                    if (verInfo.status == 1) {
                        $('.version_log').text(verInfo.verLog)
                        $(".update-btn").attr('href', verInfo.verUrl)
                    } else {
                        $(".update-btn").text(verStatus[verInfo.status])
                        if (verInfo.status == 4) {
                            clearInterval(timer);
                            $('#have_update').hide();
                            $('#no-update').show();
                        }
                    }

                }

            },
        });
    }
    function closeMsg(e) {
        e = getEvent()
        clearInterval(timer)
        if(e.target == $('#closeMsg')[0]) {
            if ($("#closeMsg>div:visible").children(".close-box-btn").hasClass("close_waiting_downcount")) {
                return
            }
            $('#first-wrap').hide();
            $("#closeMsg>div").hide();
            notifyUserClose(LastToggleAlertBox);
            LastToggleAlertBox = null;
        }
    }

    function closeMsg2(e) {
        e = getEvent()
        clearInterval(timer)
        if(e.target == $('#closeMsg-2')[0]) {
            $('#second-wrap').hide();
            $("#closeMsg-2>div").hide();
            notifyUserClose(LastToggleAlertBox2);
            LastToggleAlertBox2 = null;
        }
    }

    function closeMsg3() {
        e = getEvent()
        clearInterval(timer)
        if(e.target == $('#closeMsg-3')[0]) {
            $('#third-wrap').hide();
            $("#closeMsg-3>div").hide();
        }
    }

    function closeMsg4() {
        e = getEvent()
        clearInterval(timer)
        if(e.target == $('#closeMsg-4')[0]) {
            $('#fourth-wrap').hide();
            $("#closeMsg-4>div").hide();
            notifyUserClose(LastToggleAlertBox4);
            LastToggleAlertBox4 = null;
        }
    }

    function closeMsg5() {
        e = getEvent();
        if (e.target == $('#closeMsg-5')[0]) {
            $('#five-wrap').hide();
            $("#closeMsg-5>div").hide();
            notifyUserClose(LastToggleAlertBox5);
            LastToggleAlertBox5 = null;
        }
    }

    function notifyUserClose(box) {
        if (box && box[0]) {
            $.ajax({
                method: "POST",
                url: "ui_notify/box_close",
                data: JSON.stringify({"ui_box_class": box[0].className, "ui_box_id": box[0].id}),
                contentType: "application/json; charset=utf-8",
                success: function(data) {
                }
            });
        }
    }
    function switchbtn() {
        e = getEvent()
        toggleAlertBox($("#login"), e)
    }
    function login_mail_btn() {
        showMailLoginView();
    }
    function forget_account_btn(){
        toggleAlertBox($("#forget-pwd"),e);
    }
    
    
    
    
    

    function copy_btn(info) {
        var oInput = document.createElement('input');
        oInput.value = info;
        document.body.appendChild(oInput);
        oInput.select(); 
        document.execCommand("Copy"); 
        oInput.className = 'oInput';
        oInput.style.display='none';
        Toast("复制完成", 2000);
    }
    function disable_btn() {
        $("#pro-package").hide();
        $('#first-wrap').hide();
        $("#closeMsg>div").hide();
    }
    function signout_btn() {
        var e = getEvent()
        toggleAlertBox($("#signout_confirm"), e)
    }
    function login_phone_btn() {
        showPhoneLoginView();
    }

    function show_bind_view() {
        var e = getEvent()
        toggleAlertBox($("#bind_account"), e)
    }

    var curUserInfo = "";

    function logout_all_device(errMsg) {
        $.ajax({
            method: "POST",
            url: "device/all/logout",
            contentType: "application/json;charset=utf-8",
            data: curUserInfo,
            success: function(data) {
                if (data.code == 0) {
                    toggleAlertBox($("#logout-all-device-success"))
                } else {
                    Toast(data.msg, 2000);
                }
            }
        });
    }

    var is_signin = false;


    function signin(d, errMsg) {
        if (is_signin) {
            return;
        }
        is_signin = true;

        $.ajax({
            method: "POST",
            url: "account/switch",
            contentType: "application/json; charset=utf-8",
            data: d,
            success: function(data) {

                if (data.code == 0) {
                    location.reload();
                } else if (data.code == -2) {
                    is_signin = false;
                    
                    curUserInfo = d;
                    toggleAlertBox($("#user-over-limit"));
                } else {
                    is_signin = false;
                    if (errMsg) {
                        errMsg.text(data.msg);
                        errMsg.show();
                    }

                }
            },
        });
    }

    function show_report_problem_view() {
        var e = getEvent()
        toggleAlertBox($("#report_problem_view"), e)
        getProblemType()
    }
    $(function() {
        var isVip = false;
        if (window.zE) {
            timer = setInterval(function(){
                if(window.zE.setLocale){
                    window.zE.setLocale("zh_CN")
                    clearInterval(timer)
                }
            }, 1000)
        }
        getDiviceList();
        
        
        setLang();
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        


        $(".free-to-pro").click(function(){
            $("#pro-package").hide();
            getPlans();
            $("#update").show();
        })
        
        
        
        
        
        $(".switch-btn").on('click', function(e){
            toggleAlertBox($("#login"), e)
        })
        $(".bind-account-btn").on('click', function(e) {
            toggleAlertBox($("#bind_account"), e)
        })

        
        $("#invite_fd").on('click', function(e){
            toggleAlertBox($("#invite_box"), e);

            $.ajax({
                method: "POST",
                url: "client/action/share",
                contentType: "application/json;charset=utf-8",
                success: function(data) {}
            });
        })
        
        $("#check_update").on('click', function(e){
            getVersion(e);
        })

        
        $("#update_pro").on('click', function(e){
            e.preventDefault();
            getPlans();
            if (! true ) {
                toggleAlertBox($("#register"), e)
            } else {
                toggleAlertBox($("#update"), e);
            }
        })
        $(".upgrade-btn").on('click', function(e){
            getPlans()
            if (! true ) {
                toggleAlertBox($("#register"), e)
            } else {
                toggleAlertBox($("#update"), e);
            }
        });
        $(".renew-upgrade-btn").on("click", function (e) {
            $('#fourth-wrap').hide();
            $("#closeMsg-4>div").hide();
            notifyUserClose(LastToggleAlertBox4);
            LastToggleAlertBox4 = null;
        });

        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        
        

        var is_signuping = false;
        $("#signup-mail-form").submit(function(e) {
            e.preventDefault();
            if (is_signuping) {
                return false;
            }
            is_signuping = true;

            $.ajax({
                method: "POST",
                url: "account/signup",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify($(this).serializeObject()),
                success: function(data) {
                    if (data.code == 0) {
                        location.reload();
                    } else {
                        is_signuping = false;
                        $("#signup-mail-form-err").text(data.msg);
                        $("#signup-mail-form-err").show();
                    }
                },
            });

        });


        $("#signup-phone-form").submit(function (e) {
            e.preventDefault();

            if (is_signuping) {
                return false;
            }
            is_signuping = true;

            $.ajax({
                method: "POST",
                url: "account/signup/bindphone",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify($(this).serializeObject()),
                success : function(data) {

                    if (data.code == 0) {
                        location.reload();
                    } else {
                        is_signuping = false;
                        $("#form-err-1").text(data.msg);
                        $("#form-err-1").show();
                    }
                }
            });
        });


        $(".signin-form").submit(function(e) {
            e.preventDefault();
            curUserInfo = "";
            var curErrMsg = $(this).find("#signin-form-err")
            var switchData = JSON.stringify($(this).serializeObject())

            signin(switchData, curErrMsg);
        });

        var is_doing_forget_mail = false;
        $("#forget-mail-form").submit(function(e) {
            e.preventDefault();
            if (is_doing_forget_mail) {
                return;
            }
            is_doing_forget_mail = true;

            var f = $(this);
            $.ajax({
                method: "POST",
                url: "account/password/forget",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify(f.serializeObject()),
                success: function(data) {
                    is_doing_forget_mail = false;
                    if (data.code == 0) {
                        f.find("#forget-mail-form-err").hide();
                        alert('重置密码链接已发送到邮箱，请登录邮箱后按提示操作');
                    } else {
                        f.find("#forget-mail-form-err").text(data.msg);
                        f.find("#forget-mail-form-err").show();
                    }
                },
            });
        });

        var is_doing_forget_phone = false;
        $("#forget-phone-form").submit(function (e) {
            e.preventDefault();

            if (is_doing_forget_phone) {
                return;
            }

            is_doing_forget_phone = true;

            var f = $(this)
            $.ajax({
                method: "POST",
                url : "account/password/forget/phone",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify(f.serializeObject()),
                success: function (data) {
                    is_doing_forget_phone = false;
                    if (data.code == 0){
                        $("#first-wrap").hide()
                        alert('密码已经重置');
                    } else {
                        f.find("#form-err-2").text(data.msg);
                        f.find("#form-err-2").show();
                    }
                }
            })
        })

        var is_doing_reset_form = false;

        $("#reset-form").submit(function (e) {
            e.preventDefault();

            if (is_doing_reset_form) {
                return;
            }
            is_doing_reset_form = true;

            $.ajax({
                method: "POST",
                url: "account/password/reset",
                contentType: "application/json; charset=utf-8",
                data: JSON.stringify($(this).serializeObject()),
                success: function(data) {
                    is_doing_reset_form = false;
                    if (data.code == 0) {
                        $("#first-wrap").hide()
                        $(".login-box").hide()
                        alert('密码已经重置');
                    } else {
                        $("#reset-form-err").text(data.msg);
                        $("#reset-form-err").show();
                    }
                },
            });
        })
    })
    
    function showMailLoginView() {
        $("#login-mail-div").show();
        $("#login_mail_btn").addClass("active");
        $("#login_phone_btn").removeClass("active");
        $("#login-phone-div").hide();
    }
    
    function showPhoneLoginView() {
        $("#login-phone-div").show();
        $("#login_phone_btn").addClass("active");
        $("#login_mail_btn").removeClass("active");
        $("#login-mail-div").hide();
    }
    
    function showMailForgetPwdView() {
        $("#forget-mail-pwd").show();
        $("#forget-pwd-mail-btn").addClass("active");
        $("#forget-pwd-phone-btn").removeClass("active");
        $("#forget-phone-pwd").hide();
    }
    
    function showPhoneForgetPwdView() {
        $("#forget-phone-pwd").show();
        $("#forget-pwd-phone-btn").addClass("active");
        $("#forget-pwd-mail-btn").removeClass("active");
        $("#forget-mail-pwd").hide();
    }

    
    function showMailBindView() {
        $("#bind_phone").hide();
        $("#bind_phone_account_btn").removeClass("active");
        $("#bind_mail_account_btn").addClass("active");
        $("#bind_mail").show();
    }
    
    function showPhoneBindView() {
        $("#bind_phone").show();
        $("#bind_phone_account_btn").addClass("active");
        $("#bind_mail_account_btn").removeClass("active");
        $("#bind_mail").hide();
    }

    
    function showPaidNotificationView() {

        if ( 10  > 0) {
            var closeSecs =  10 ;
            var waitingCtrls = $("#paid_notification .close-downcount");
            var closeBtn = $("#paid_notification .close-box-btn");
            var bindLaterBtn = $("#paid_notification .bind_later");

            if (!(waitingCtrls.hasClass("close_waiting_downcount"))){
                waitingCtrls.addClass("close_waiting_downcount");
            }
            closeBtn.addClass("close-box-btn-bk");

            var originText = bindLaterBtn.text();
            waitingCtrls.text(closeSecs + "S");
            var downcnt = closeSecs;
            var paidNotificationTimer = setInterval(function () {
                downcnt --;
                if (downcnt <= 0){
                    closeBtn.text('');
                    bindLaterBtn.text(originText);
                    waitingCtrls.removeClass("close_waiting_downcount");
                    closeBtn.removeClass("close-box-btn-bk");
                    clearInterval(paidNotificationTimer);
                    return
                }
                downcnt > 9 ?  waitingCtrls.text(downcnt + "S") :  waitingCtrls.text("0" + downcnt + "s");
            }, 1000);
        }
        toggleAlertBox($("#paid_notification"));
    }

    function getPlans() {
        var plans = {};
        var selectedPlan = null;
        var lastPurchaseTimestamp = 0;
        var hotstr_template = '<span class="recommend" style="background-image: url(\'.\/static\/sb\/dist\/img\/icon\/icon_hot_zh.png\')"></span>'
        $.ajax({
            method: "GET",
            url: "payment/plan",
            success: function(data) {
                $(".select-item").empty();
                var all = JSON.parse(data);
                for (var i in all) {
                    var p = all[i];
                    plans[p.plan_id] = p;
                    var hotstr = ""
                    if (p.hot) {
                        hotstr = hotstr_template
                    }
                    $(".select-item").append(
                            '<div class="select-row ' + p.plan_id + '">' +
                            '<div class="no-name-item">' + p.no_name + '</div>' +
                            '<div class="left-item"><div><span>' + p.name + '</span>'+
                            '</div>' + '<div class="discount-tips">' + p.note +'</div>' +
                            '</div>' +
                            '<div class="price">' +
                            '<div>' +
                            '<p>' + p.price_str + '</p>' +
                            '<p>' + p.ori_price_str + '</p>' +
                            '<p>立即购买</p>' +
                            '</div>' +
                            '<i class="ff-icon icon-arrow-right"></i>' +
                            '</div>' +
                            hotstr +
                            '</div>'
                    )
                }
                $('.select-row').click(function () {
                    for(var i in plans) {
                        if ($(this).hasClass(i)) {
                            selectedPlan = plans[i];
                            var curTimestamp = new Date().getTime()
                            if (curTimestamp - lastPurchaseTimestamp < 10000){
                                console.log("curTimestamp " + curTimestamp + "lastPurchaseTimestamp " + lastPurchaseTimestamp)
                                return
                            }
                            lastPurchaseTimestamp = curTimestamp
                            var left = screen.width/2 - 500;
                            var top = screen.height/2 - 300;

                            var newWin = window.open('payment/loading','Payment','scrollbars=yes,resizable=yes,location=no,width=1000,height=600,screenX='+left+',screenY='+top+',left='+left+',top='+top);
                            
                            $.ajax({
                                method: "POST",
                                url: "payment/stripe/alipay",
                                contentType: "application/json; charset=utf-8",
                                data: JSON.stringify({
                                    plan_id : selectedPlan.plan_id,
                                    plan_name: selectedPlan.name,
                                }),
                                success: function(data) {
                                    if (data.code == 0) {
                                        $("#first-wrap").hide();
                                        
                                        
                                        newWin.location.href = data.data.redirect
                                    } else {
                                        newWin.close()
                                        alert(data.msg)
                                    }
                                },
                                error: function() {
                                }
                            });
                        }
                    }
                })
            },
        });
    }

    function popUpNotices() {
        $.ajax({
            method: "GET",
            url: "notices/need_popup",
            success: function (data) {
                if (data.code == 0) {
                    if (data.data.need_popup) {
                        e = getEvent();
                        e.preventDefault();
                        setNoticesData(data.data.notices);
                        toggleAlertBox2($("#notice-pane"),e)
                    }
                } else {
                    setTimeout(function () {
                        popUpNotices();
                    }, 2000);
                }
            }
        })
    }

    function setNoticesData(data) {
        if (data.length <= 0) {
            var EmptyTips = '<div class="sub-notice">\n' +
                    '<div class="sub-notice-title">\n' +
                    '<span class="sub-notice-title-type">暂无公告</span>\n' +
                    '<span class="sub-notice-title-date"></span>\n' +
                    '</div>\n' +
                    '<div class="sub-notice-content">\n' +
                    '</div>\n' +
                    '</div>';
            $(".notice-pane-content").append(EmptyTips);
            return
        }

        for (var i in data) {
            var notice = data[i];
            var link = '';
            if (notice.link.length > 0) {
                link = ' onclick="window.open(\'' + notice.link + '\')" ';
            }

            var notice_html = '<div class="sub-notice"' + link +'>' +
                    '<div class="sub-notice-title">' +
                    '<span class="sub-notice-title-type">' + notice.title + '</span>' +
                    '<span class="sub-notice-title-date">' + notice.date + '</span>' +
                    '</div>' +
                    '<div class="sub-notice-content">' + notice.content + '</div>';

            if (notice.link.length > 0) {
                notice_html += '<div class="sub-notice-button-container">' +
                        '<a class="sub-notice-button" target="_blank" href="' + notice.link + '">查看</a>'
                        + '</div>';
            }
            notice_html += '</div>';
            $(".notice-pane-content").append(notice_html)
        }
    }

    function getNotices() {
        $(".notice-pane-content").empty();

        $.ajax({
            method: "GET",
            url: "notices",
            success: function(data) {
                if (data.code == 0) {
                    setNoticesData(data.data);
                }
            },
        });
    }

    
    function getProblemType() {
        $.ajax({
            method: "GET",
            url: "problem/types",
            success: function (data) {
                if (data.code == 0) {
                    if (data.data) {
                        e = getEvent();
                        if (e && e.preventDefault) {
                            e.preventDefault();
                        }
                        setProblemType(data.data);
                        
                        
                    }
                } else if (data.code == 7000) {
                    Toast("您当前的网络不可用或太差，请检查您的网络再重试", 3000);
                } else {
                    
                    
                    
                    
                }
            }
        })
    }
    
    function setProblemType(data) {
        if (data.length <= 0) {
            $("#problem_type").innerHTML = "";
            return
        }
        var problemHTML = ''
        for (var i in data) {
            var problemType = data[i];
            var problemTypehtml = '<option value="' + problemType.replace(/\"/g, "&quot;") +'">' + problemType + "</option>";
            problemHTML += problemTypehtml;
        }
        $("#problem_type")[0].innerHTML = problemHTML;
    }

    var LastToggleAlertBox2;

    function toggleAlertBox2(boxId, e) {
        if (e && e.preventDefault) {
            e.preventDefault();
        }
        $("#closeMsg-2>div").hide();
        $("#second-wrap").show();
        boxId.show();
        LastToggleAlertBox2 = boxId;
    }

    var LastToggleAlertBox5;

    function toggleAlertBox5(boxId, e) {
        if (e && e.preventDefault) {
            e.preventDefault();
        }
        $("#closeMsg-5>div").hide();
        $("#five-wrap").show();
        boxId.show();
        LastToggleAlertBox5 = boxId;
    }

    var LastToggleAlertBox4;

    function toggleAlertBox4(boxId, e) {
        if (e && e.preventDefault) {
            e.preventDefault();
        }
        $("#closeMsg-4>div").hide();
        $("#fourth-wrap").show();
        boxId.show();
        LastToggleAlertBox4 = boxId;
    }

    function toggleAlertBox3(boxId, e) {
        if (e && e.preventDefault) {
            e.preventDefault();
        }
        document.querySelector("#closeMsg-3>div").style["display"] = "none";
        document.querySelector("#third-wrap").style["display"] = "block";
        document.querySelector(boxId).style["display"] = "block";
        $("#closeMsg-3>div").hide();
        $("#third-wrap").show();
        $(boxId).show();
    }

    var LastToggleAlertBox;
    function toggleAlertBox(boxId, e) {
        if (e && e.preventDefault) {
            e.preventDefault();
        }
        $("#closeMsg>div").hide();
        $("#first-wrap").show();
        boxId.show();
        LastToggleAlertBox = boxId;
    }
    function setLocalItem (name, val) {
        
        if (typeof val === 'object' || Array.isArray(val)) {
            val = JSON.stringify(val)
        }
        localStorage.setItem(name, val)
    }
    function getLocalItem (name) {
        var val = localStorage.getItem(name);
        try {
            return JSON.parse(val)
        } catch (e) {
            return val
        }
    }

    popUpNotices();

    $(".number-control").on("keydown", function (event) {
        var eventCode = event.which ? event.which : window.event.keyCode;
        var isShiftPressed = (event.shiftKey == 1);

        var maxlength = this.getAttribute("maxlength");
        var curlength = this.value.length;


        if (eventCode == 8 
                || eventCode == 46 
                || eventCode == 37 || eventCode == 39 
           ) {
            return true;
        }
        if ((eventCode >= 48 && eventCode <= 57 && !isShiftPressed) || (eventCode >= 96 && eventCode <= 105) 
           ) {
            if (!maxlength || maxlength && curlength < maxlength) {
                return true;
            }
        }
        return false;
    });

    $(function() {
        $("#side-menu").metisMenu();
    }),
    $(function() {
        $(window).bind("load resize", function() {
            var i = 50,
                    n = this.window.innerWidth > 0
                            ? this.window.innerWidth
                            : this.screen.width;
            n < 768
                    ? ($("div.navbar-collapse").addClass("collapse"), (i = 100))
                    : $("div.navbar-collapse").removeClass("collapse");
            var e =
                    (this.window.innerHeight > 0
                            ? this.window.innerHeight
                            : this.screen.height) - 1;
            (e -= i),
            e < 1 && (e = 1),
            e > i && $("#page-wrapper").css("min-height", e + "px");
        });
        for (var i = window.location, n = $("ul.nav a").filter(function() {return this.href == i;}).addClass("active").parent(); ; ) {
            if (!n.is("li")) break;
            n = n
                    .parent()
                    .addClass("in")
                    .parent();
        }
    });
</script>



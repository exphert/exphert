


###  *./AboutMe.php*
```php
<?php

class AboutMe {
    public static function Welcome(){
        return "
        _ _ _     _                      _____        _____        _____         ___ _ _
       | | | |___| |___ ___ _____ ___   |_   _|___   |     |_ _   |  _  |___ ___|  _|_| |___
       | | | | -_| |  _| . |     | -_|    | | | . |  | | | | | |  |   __|  _| . |  _| | | -_|
       |_____|___|_|___|___|_|_|_|___|    |_| |___|  |_|_|_|_  |  |__|  |_| |___|_| |_|_|___|
                                                           |___|
       ";
    }

    public static function Profile(){
        return [
            ["Name    " => "Surya Hadini .S"],
            ["Live In " => "𝚆𝚎𝚜𝚝 𝙹𝚊𝚟𝚊, 𝙸𝚗𝚍𝚘𝚗𝚎𝚜𝚒𝚊"],
            ["𝚂𝚝𝚞𝚍𝚢𝚒𝚗𝚐" => "𝙵𝚞𝚕𝚕𝚜𝚝𝚊𝚌𝚔 𝙳𝚎𝚟𝚎𝚕𝚘𝚙𝚎𝚛, 𝙲𝚢𝚋𝚎𝚛𝚂𝚎𝚌𝚞𝚛𝚒𝚝𝚢"],
            ["Using OS" => "Windows, Linux"],
            ["Skills  " => "𝙷𝚃𝙼𝙻, 𝙲𝚂𝚂, 𝙿𝙷𝙿, 𝙹𝚊𝚟𝚊𝚂𝚌𝚛𝚒𝚙𝚝, 𝙿𝚢𝚝𝚑𝚘𝚗, 𝙹𝚊𝚟𝚊, 𝙲/C++"],
            ["𝙻𝚊𝚗𝚐𝚞𝚊𝚐𝚎" => "𝙱𝚊𝚑𝚊𝚜𝚊 𝙸𝚗𝚍𝚘𝚗𝚎𝚜𝚒𝚊, 𝚂𝚞𝚗𝚍𝚊𝚗𝚎𝚜𝚎, 𝙴𝚗𝚐𝚕𝚒𝚜𝚑"],
        ];
    }
}

?>
```
<div style="display:grid;  gap: 10px; color:#FF6E96; grid-template-columns: repeat(2, minmax(0, 1fr));">
    <pre style="background:#282A36; height:100%; font-size: 0.6rem; border-radius:10px; padding-top:1rem; display:flex; justify-content:center; align-items:center;">
⣇⣿⠘⣿⣿⣿⡿⡿⣟⣟⢟⢟⢝⠵⡝⣿⡿⢂⣼⣿⣷⣌⠩⡫⡻⣝⠹⢿⣿⣷
​⡆⣿⣆⠱⣝⡵⣝⢅⠙⣿⢕⢕⢕⢕⢝⣥⢒⠅⣿⣿⣿⡿⣳⣌⠪⡪⣡⢑⢝⣇
​⡆⣿⣿⣦⠹⣳⣳⣕⢅⠈⢗⢕⢕⢕⢕⢕⢈⢆⠟⠋⠉⠁⠉⠉⠁⠈⠼⢐⢕⢽
​⡗⢰⣶⣶⣦⣝⢝⢕⢕⠅⡆⢕⢕⢕⢕⢕⣴⠏⣠⡶⠛⡉⡉⡛⢶⣦⡀⠐⣕⢕
​⡝⡄⢻⢟⣿⣿⣷⣕⣕⣅⣿⣔⣕⣵⣵⣿⣿⢠⣿⢠⣮⡈⣌⠨⠅⠹⣷⡀⢱⢕
​⡝⡵⠟⠈⢀⣀⣀⡀⠉⢿⣿⣿⣿⣿⣿⣿⣿⣼⣿⢈⡋⠴⢿⡟⣡⡇⣿⡇⡀⢕
​⡝⠁⣠⣾⠟⡉⡉⡉⠻⣦⣻⣿⣿⣿⣿⣿⣿⣿⣿⣧⠸⣿⣦⣥⣿⡇⡿⣰⢗⢄
​⠁⢰⣿⡏⣴⣌⠈⣌⠡⠈⢻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣬⣉⣉⣁⣄⢖⢕⢕⢕
​⡀⢻⣿⡇⢙⠁⠴⢿⡟⣡⡆⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣵⣵⣿
​⡻⣄⣻⣿⣌⠘⢿⣷⣥⣿⠇⣿⣿⣿⣿⣿⣿⠛⠻⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿
​⣷⢄⠻⣿⣟⠿⠦⠍⠉⣡⣾⣿⣿⣿⣿⣿⣿⢸⣿⣦⠙⣿⣿⣿⣿⣿⣿⣿⣿⠟
​⡕⡑⣑⣈⣻⢗⢟⢞⢝⣻⣿⣿⣿⣿⣿⣿⣿⠸⣿⠿⠃⣿⣿⣿⣿⣿⣿⡿⠁⣠
​⡝⡵⡈⢟⢕⢕⢕⢕⣵⣿⣿⣿⣿⣿⣿⣿⣿⣿⣶⣶⣿⣿⣿⣿⣿⠿⠋⣀⣈⠙
⡝⡵⡕⡀⠑⠳⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⢉⡠⡲⡫⡪⡪⡣
    </pre>
    <div style="background:#282A36; border-radius:10px;">
      <ul style="padding: 0; margin:0; list-style-type: none; ">
        <li style="padding: 0.5rem 1rem; width: 100%;">
            <span style="color:#FF5555;">𝖗𝖔𝖔𝖙 <span style="color:#fff;">λ</span> 𝖘𝖆𝖓𝖘𝖝𝖕𝖑</span>
            <hr style="padding:0; margin:0;">
        </li>
      </ul>
      <table style="border-collapse: collapse; font-size:0.8rem; width: 100%;">
        <tbody>
          <tr style="border-bottom: 1px solid #5C5E70;">
            <td style="color:#BD93F9; font-style:italic; width:30%; padding: 0 10px;">Name</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> Surya Hadini .S</td>
          </tr>
          <tr style="border-bottom: 1px solid #5C5E70;">
            <td style="color:#BD93F9; font-style:italic; padding: 0 10px;">Live In</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> West Java, Indonesia</td>
          </tr>
          <tr style="border-bottom: 1px solid #5C5E70;">
            <td style="color:#BD93F9; font-style:italic; padding: 0 10px;">Studiying</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> Fullstack Dev, CyberSecurity</td>
          </tr>
          <tr style="border-bottom: 1px solid #5C5E70;">
            <td style="color:#BD93F9; font-style:italic; padding: 0 10px;">Using OS</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> Windows, Linux</td>
          </tr>
          <tr style="border-bottom: 1px solid #5C5E70;">
            <td style="color:#BD93F9; font-style:italic; padding: 0 10px;">Skills</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> HTML, CSS, JavaScript, PHP, Python, Java, C/C++</td>
          </tr>
          <tr >
            <td style="color:#BD93F9; font-style:italic; padding: 0 10px;">Languages</td>
            <td style="color:#fff; padding-right: 10px; padding-bottom:5px;"> Bahasa Indonesia, Sundanese, English</td>
          </tr>
        </tbody>
      </table>
    </div>
</div>
<hr>
<div style="display:grid;  gap: 10px; color:#FF6E96; grid-template-columns: repeat(2, minmax(0, 1fr));">
    <div style="background:#282A36; border-radius:10px;">
      <span style="background:#282A36; font-size: 1.3rem; letter-spacing: 0.025em; border-radius:10px; padding:5px; display:flex; justify-content:center; align-items:center;">
        𝕻𝖎𝖓𝖓𝖊𝖉 𝕽𝖊𝖕𝖔𝖘𝖎𝖙𝖔𝖗𝖞𝖘
      </span>
      <ul style="margin: 1rem;  margin-top:5px; padding: 0; list-style-type: none; ">
        <li style="display:grid; padding: 0.5rem 1rem; background-color: #1F212B; border-radius: 0.5rem; width: 100%;">
            <a href="#" style="font-size: 1.1rem; font-style:italic; text-decoration:none; display: inline-flex; align-items: center; color: #BD93F9;">
                sansxpl/
            </a><hr style="padding:0; margin:0;">
            <span style="color:#dee2ff;">tes</span>
        </li>
    </ul>
    </div>
    <div style="display:grid; gap: 10px;">
      <div style="background:#282A36; border-radius:10px; padding-bottom:5px">
        <span style="margin-top:5px; font-size: 1.3rem; letter-spacing: 0.025em; display:flex; justify-content:center; align-items:center;">
          𝕸𝖞 𝕲𝖎𝖙𝖍𝖚𝖇 𝕾𝖙𝖆𝖙𝖘
        </span>
        <img src="https://github-readme-stats.vercel.app/api?username=sansxpl&show_icons=true&hide_title=true&hide_border=true&theme=dracula&text_color=dee2ff&icon_color=BD93F9" align=right/>
      </div>
      <div style="background:#282A36; border-radius:10px;">
        <span style="margin-top:5px; font-size: 1.3rem; letter-spacing: 0.025em; display:flex; justify-content:center; align-items:center;">
          𝕸𝖔𝖘𝖙 𝖀𝖘𝖊𝖉 𝕷𝖆𝖓𝖌𝖚𝖆𝖌𝖊𝖘
        </span>
        <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=sansxpl&show_icons=true&hide_border=true&hide_title=true&theme=dracula&include_all_commits=true&count_private=false&layout=compact&text_color=dee2ff" align=right/>
      </div>
    </div>
</div>


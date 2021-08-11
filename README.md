- 👋 Hi, I’m @Jafar00g
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Jafar00g/Jafar00g is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
if ($text == "/time"){
    $get_time = time() + (979 * 11 + 1 + 30);
    $time =  date('g', $get_time).":".date('i', $get_time);
    $data = date('Y-m-d');
    bot('sendMessage',[
        'chat_id'=>$chat_id,
        'text'=>"time is $time
data is $data",
        'disable_web_page_preview'=>'yes',]);
}

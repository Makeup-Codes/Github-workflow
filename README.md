# Github-workflow

So আমরা অনেকেই এখনো আমাদের github workflow টা নিয়ে পুরোপুরি ভাবে clear না তাই
আমি কিভাবে কি করতে হবে তা Shortly বলে দিচ্ছি আশা করি সবাই পরে নিবানে ।

তার আগে কিছু Basic command you need to knowঃ-
1.git pull - (এই command দিয়ে আমরা remote এ কোনো নতুন branch create হলে তা Loacl machine এও পেতে পারি)।

2.git pull origin [branch_name] - (এই command দিয়ে আমরা আমদের নিজেদের branch development বা যে কোনো branch এর updated code টা পেতে পারি)।

3.git checkout -b [TaskName/yourName] - (এই এই command দিয়ে আমরা নতুন branch create করতে পারি )।

4.git checkout [branch_name] - (এই command দিয়ে আমরা আমাদের existing branch এ switch করতে পারি )।

5.git branch - (এই এই command দিয়ে আমরা আমাদের local branch কয়টা আছে  এবং কি কি তা দেখতে পারি )।

6.git branch -d [localBranchName] - (এই command দিয়ে আমরা আমাদের local branch Delete করে দিতে পারি)।

7.git push origin [your_Branch_Name] - (এই command দিয়ে আমরা আমাদের  branch এ code push করে  করে দিতে পারি)।


এবার কাজের কথায় আসিঃ-
১। আমরা আমাদের project টা কে clone করার পর সবাই  প্রথম এ যে কাজটা করব তা হলো উপরের 4 no
command টা দিয়ে development branch এ switch করে নিব ভুলেও কেও main branch এ থাকব ন।

২। Then আপনদর ক য কজ ট দয় হব তর নম and আপনর নজর নম দয় একট new branch create কর নব। Eample 
যদ আপনর Task যদ registration part হয় তহল register/yourName দয় branch ট create কর নব। আর এর জনয command
ট হব 3 no। 

৩। Then ওখন আপনর নজদর কজ ট শষ কর ।  git add . then git commit -m "" কর 
development branch টক pull কর নব (2 no command) দয় যত  updated কড ট পয় যন। এর পর আমর নজদর কড ট ক নজদর branch এ push কর দব (7 no command দয়)। এব পরতবর নজদর branch এ কড push করর আগ এই কজ ট আরকবর repeat করব।

৪। lastly আমর আমদর সবর কজ গল যখন শষ কর ফলব presentation শষ হয় যব তখন আম বলল সবই নজদর  যই যই branch create কর কজ করছলম ত locally delete কর দব (6 no command দয় করত হয়)।

এভবই কজ ট চলত থকব।

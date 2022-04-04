# Github-Workflow

> SO আমরা অনেকেই এখনো আমাদের GITHUB WORKFLOW টা নিয়ে পুরোপুরি ভাবে CLEAR না তাই
আমি কিভাবে কি করতে হবে তা SHORTLY বলে দিচ্ছি আশা করি সবাই পরে নিবানে ।

##### *তার আগে কিছু Basic command you need to know:-*

1. `git pull` - (এই command দিয়ে আমরা remote এ কোনো নতুন branch create হলে তা Local machine এও পেতে পারি / main branch or development branch locally updated করতে ও এই command use করা হয়)।

3. `git pull origin [branch_name]` - (এই command দিয়ে আমরা আমদের নিজেদের branch  বা যে কোনো branch এর updated code টা পেতে পারি)।

5. `git checkout -b [TaskName/yourName]` - (এই command দিয়ে আমরা নতুন branch create করতে পারি )।

7. `git checkout [branch_name]` - (এই command দিয়ে আমরা আমাদের existing branch এ switch করতে পারি )।

9. `git branch `- (এই এই command দিয়ে আমরা আমাদের local branch কয়টা আছে  এবং কি কি তা দেখতে পারি )।

11. `git branch -d [localBranchName]` - (এই command দিয়ে আমরা আমাদের local branch Delete করে দিতে পারি)।

13. `git push origin [your_Branch_Name]` - (এই command দিয়ে আমরা আমাদের  branch এ code push করে  করে দিতে পারি)।


### এবার কাজের কথায় আসি:-


- আমরা আমাদের Project টা কে Clone করার পর সবাই  প্রথম এ যে কাজটা করব তা হলো উপরের 4 No Command টা দিয়ে Development Branch এ Switch করে নিব ভুলেও কেও Main Branch এ থাকব না।

- Then আপনাদের কে যে কাজ টা দেয়া হবে তার নাম and আপনার নিজের নাম দিয়ে একটা new branch create করে নিবো। Eample যদি আপনার Task যদি registration part হয় তাহলে register/yourName দিয়ে branch টা create করে নিব। আর এর জন্য command টা হবে 3 no

- Then ওখানে আপনারা নিজেদের কাজ টা শেষ করে ।  git add . then git commit -m "" করে development branch টাকে pull করে নিব (2 no command) দিয়ে যাতে  updated কোড টা পেয়ে যান। এর পর আমরা নিজেদের কোড টা কে নিজেদের branch এ push করে দিব (7 no command দিয়ে)। এবং প্রতিবার নিজেদের branch এ কোড push করার আগে এই কাজ টা আরেকবার repeat করবো।

- lastly আমরা আমদের সবার কাজ গুলা যখন শেষ করে ফেলব presentation শেষ হয়ে যাবে তখন আমি বললে সবাই নিজেদের  যেই যেই branch create করে কাজ করেছিলাম তা locally delete করে দিব (6 no command দিয়ে করতে হয়)।

#####  **এভাবেই কাজ টা চলতে থাকবে। **


# শুরু কথাঃ
- আপনি লিনাক্স ইনস্টল করে থাকলে স্বাগতম। এতক্ষণ আপনার অপেক্ষাই করছিলাম।
- না করে থাকলে অবশ্যই ইনস্টল করে ফেলুন। আর স্বাদ নিন মুক্ত এবং বিনামুল্যের প্রযুক্তির।

# শুরুর পরেঃ
### ধরে নিলাম আপনি লিনাক্স ইনস্টল করেছেন এবং এটি ডেবিয়ান ভিত্তিক। এবার আপনার পরবর্তি কাজের একটা তালিকাঃ
- টার্মিনালে চালানঃ ```sudo apt update && sudo apt upgrade```
- বাহ আপনি আপনার সিস্টেম আপডেট ও আপগ্রেড করে ফেলেছেন। এবার কিছু বাড়তি টুল ইনস্টল করে নেয়া লাগবে। কোড এডিটর হিসেবে আমার ভিম এবং সাবলাইম পছন্দ।
  - vim ইনস্টল করতেঃ ```sudo apt install vim -y```
  - মিন্টে gedit পাই নাই আমি। এটাও বেশ ভালো। ইনস্টল করতেঃ ```sudo apt install gedit -y```
  - sublime ইনস্টল করতে পরপর নিচের কমান্ডগুলা চালানঃ 
    - ```wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add -```
    - ```echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list```
    - ```sudo apt update```
    - ```sudo apt install sublime-text```
    - টার্মিনালে ```subl``` টাইপ করে দেখতে পারেন Sublime Text ইনস্টল হয়েছে কিনা।
- যারা গুগল ক্রোম ব্যাবহার করেন তারা হয়তো একে মিস করছেন। মিস করে কি লাভ! ইনস্টল করে ফেলুন নিচের কমান্ডগুলো চালিয়েঃ 
  - ```wget -q -O - https://dl-ssl.google.com/linux/linux_signing_key.pub | sudo apt-key add -```
  - ```echo 'deb [arch=amd64] http://dl.google.com/linux/chrome/deb/ stable main' | sudo tee /etc/apt/sources.list.d/google-chrome.list```
  - ```sudo apt update```
  - ```sudo apt install google-chrome-stable```
- ভালো কথা! git তো ইনস্টল করা নেই! ওপেনসোর্স প্রোজেক্টগুলো কমান্ডলাইনে ডাউনলোড করবেন কিভাবে? বা যদি এই লেখাটাই সংশোধন এর জন্য সুপারিশ করবেন কিভাবে? বা যদি আপনি আাপনার প্রোজেক্টের ভার্শন কন্ট্রোল করতে চান? চলুন ইনস্টল করে ফেলি। ঝামেলা কারই বা ভাল্লাগে...
    - ```sudo apt install git -y```
- মিস করে গিয়েছিলাম! :cry: পাইথন তো আছেই ইনস্টল করা। কিন্তু pip তো নাই! তাহলে পাইথনের মডিউলগুলো নামাবেন কিভাবে? অথবা পাইথন অ্যাপ্লিকেশনগুলো কিভাবে সরাসরি ইনস্টল করবেন? চলেন ইনস্টল করে ফেলি নিচের কমান্ড চালিয়েঃ
    - ```sudo apt install python-pip``` এই কমান্ডটা পাইথন ৩ এর pip ইনস্টল করবে। পাইথণ ২ pip ইনস্টল করতে পরবর্তি কামন্ড চালান।
    - ```sudo apt install python3-pip```

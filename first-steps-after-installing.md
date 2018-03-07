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


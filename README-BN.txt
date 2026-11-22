RUBEL VIDEO STUDIO - Android APK Build

এই ZIP-এ আপনার মূল ৫টি ফাইল অপরিবর্তিত রাখা হয়েছে। সঙ্গে Capacitor configuration ও GitHub Actions workflow যোগ করা হয়েছে।

মোবাইল থেকে APK তৈরির ধাপ:
1. ZIP Extract করুন।
2. GitHub-এ সাইন ইন করে New repository তৈরি করুন; নাম দিন rubel-video-studio। Public বা Private যেকোনোটি হতে পারে।
3. Extract করা ফোল্ডারের ভেতরের সব ফাইল ও .github ফোল্ডারসহ repository-র root-এ upload করুন। শুধু ZIP ফাইল upload করবেন না।
4. GitHub repository-র Actions tab খুলুন। প্রথমবার workflow চালাতে Enable workflows/Allow actions দেখালে অনুমতি দিন।
5. বাম পাশে Build RUBEL VIDEO STUDIO APK নির্বাচন করে Run workflow চাপুন।
6. Build শেষ হলে সবুজ Success দেখাবে। সেই run খুলে নিচের Artifacts থেকে rubel-video-studio-debug-apk ডাউনলোড করুন।
7. ZIP extract করে app-debug.apk ইনস্টল করুন। Android জিজ্ঞেস করলে Chrome/GitHub/Files-এর জন্য Install unknown apps অনুমতি দিন।

গুরুত্বপূর্ণ:
- এটি প্রাথমিক Debug APK; Play Store-এ প্রকাশের জন্য Signed Release APK আলাদাভাবে তৈরি করতে হবে।
- APK তৈরি হওয়া মানেই প্রতিটি ভিডিও এডিটিং ফিচার Android-এ নিখুঁতভাবে চলবে—এমন নয়। ফোনে পরীক্ষা করতে হবে।
- Freesound API token কখনো প্রকাশ্য GitHub repository বা অ্যাপের JavaScript-এ রাখবেন না।
- appId com.rubel.videostudio; পরে Play Store-এ প্রকাশের আগে স্থায়ী package ID ঠিক করে নেবেন।

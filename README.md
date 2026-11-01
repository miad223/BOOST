# BOOST — Personal Autonomous AI Agent for Android (Android 14, 15, 16)

একটি সম্পূর্ণ Native Kotlin + Jetpack Compose Android অ্যাপ প্রজেক্ট, যেখানে আপনার মাস্টার প্রজেক্ট প্ল্যানের **২২টি কোর মডিউল**, **অটোনোমাস বিহেভিয়ার**, এবং **কঠোর সেফটি রুলস** একীভূত করা হয়েছে।

## কম্পিউটার ছাড়াই মোবাইল থেকে সরাসরি ইনস্টলযোগ্য `.apk` ডাউনলোড করার নিয়ম (GitHub Actions অটোমেটেড বিল্ড):

১. আপনার মোবাইল ব্রাউজার থেকে [GitHub.com](https://github.com)-এ লগইন করে একটি নতুন Repository তৈরি করুন (যেমন: `BOOST-Android-Agent`)।
২. এই `BOOST_Android_Project.zip` ফাইলের ভেতরের সব ফাইল GitHub রেপোজিটরিতে আপলোড করুন (অথবা Git দিয়ে Push করুন)।
৩. আপলোড করার সাথে সাথেই `.github/workflows/build-apk.yml` স্বয়ংক্রিয়ভাবে চালু হবে এবং GitHub-এর ক্লাউড সার্ভারে Android SDK 35 ও JDK 17 ব্যবহার করে **Debug ও Release APK** বিল্ড করবে।
৪. ২–৩ মিনিট পর আপনার GitHub রেপোজিটরির **Actions** বা **Releases** ট্যাবে গেলে সরাসরি **`BOOST-v1.0.0-debug.apk`** ডাউনলোড করে আপনার Android 14, 15 বা 16 ফোনে ইনস্টল করতে পারবেন।

## পিসিতে (Android Studio) বিল্ড করার কমান্ড:
```bash
./gradlew assembleDebug
```
আউটপুট APK পাওয়া যাবে: `app/build/outputs/apk/debug/app-debug.apk`

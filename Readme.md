### 6. Answer the following questions clearly:

1. What is the difference between **getElementById, getElementsByClassName, and querySelector / querySelectorAll**?
Ans:getElementById হল একটি নিদিষ্ট এলিমেন্টের আইডি দিয়ে সিলেক্ট করা।getElementsByClassName হল একটি ক্লাস সিলেক্ট করা যার মধ্যে অনেক গুলো
এলিমেন্ট থাকে।querySelector দিয়ে একটি আইটেম সিলেক্ট করে যে রিটার্ন পাওয়া যায় তাই ।querySelectorAll হল একটি ক্লাসের ভিতর থাকা সব গুলো ক্লাস কে সিলেক্ট করে ফাংশনাল করতে ব্যবহার করা হয়।
================================================================
2. How do you **create and insert a new element into the DOM**?
Ans:document.createElement() মেথড ব্যবহার করে একটি নতুন এলিমেন্ট তৈরি করা যায়।এবং এই মেথডে স্ট্রিং ও রাখা যায়।
===============================================================
3. What is **Event Bubbling** and how does it work?
Ans:Event Bubbling হলো একটি প্রক্রিয়া যেখানে একটি চাইল্ড এলিমেন্টে কোনো ঘটনা (/ক্লিক করা) ঘটলে, সেই একই ঘটনা তার প্যারেন্ট এলিমেন্টগুলোতেও  ঘটে ।
===============================================================
4. What is **Event Delegation** in JavaScript? Why is it useful?
Ans:ইভেন্ট ডেলিগেশন হলো অনেকগুলো চাইল্ডের জন্য প্যারেন্ট এলিমেন্টের উপর একটিমাত্র ইভেন্ট লিসেনার ব্যবহার করা।
================================================================
5. What is the difference between **preventDefault() and stopPropagation()** methods?
Ans:preventDefault() ওয়েল এবং সেকশনের মধ্যে ক্লিক  করতে  এটা ব্যবহার করা হয়। stopPropagation() ওয়েল এবং সেকশনের মধ্যে ক্লিক বন্ধ করতে  এটা ব্যবহার করা হয়।
=====================================================================

---
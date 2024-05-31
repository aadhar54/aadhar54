### Hi there, I'm **Aadhar** 👋 

I believe that "For a person who is ready to put in extra efforts, nothing is impossible."

<img src="https://img1.wsimg.com/isteam/stock/V5yGK9n/:/rs=w:1200,h:600,cg:true,m/cr=w:1200,h:600" height="200px"><img src="https://assets.leetcode.com/static_assets/marketing/2024-50.gif" height="200px">

DSA syntax : https://drive.google.com/file/d/1ao4ZA28zzBttDkuS6MLQI52gDs_CJZEm/view

Grokking System Design Book : https://drive.google.com/file/d/1qVYf8nbmoFh1nNtA9IrCNt_t5Dv2zkXD/view?usp=sharing

Grokking the Java Interview : https://drive.google.com/file/d/1kB8Rfc22f3m-b9wLbABRBxJBTrgGIWam/view?usp=sharing




<img src="./aadhar54.jpeg" height="200px">

Read my latest blog at https://aadhar.hashnode.dev/two-years-in-it ✅ <br/>
Please review my latest career portfolio at https://aadhar54.github.io/ ✅ 

## I'm a `prudent and motivated` Back End Developer , Teacher and self proclaimed Philosopher !!

- My dream is to spend my life `building products` and become a `Software Soldier` 🔭💛
- I believe in building long-lasting relationships that translate into high-performing teams. 
- I’m currently building projects with React and Spring Boot🔵
- I love to help people with doubts in projects ❤️
- 2021 Goals: Work to Level up my proficiency in `Typescript` 🔥
- Fun fact: I am an ardent fan of Indian Comedy Scene 🟩
- My favourite song is Iktara from Wake Up Sid 🌦️


### 📌 My technical skills include :

 - 💻 *Languages:*  <img align="center" height="30" src="https://img.icons8.com/color/144/000000/javascript.png"/> <img align="center" height="30" src="https://img.icons8.com/ultraviolet/480/000000/react.png"/>

 - 💻 *Front-End Development:* <img align="center" height="30" src="https://img.icons8.com/color/144/000000/html-5.png"/> <img align="center" height="30" src="https://img.icons8.com/color/144/000000/css3.png"/> <img align="center" height="30" src="https://img.icons8.com/color/144/000000/javascript.png"/> <img align="center" height="30" src="https://img.icons8.com/ultraviolet/480/000000/react.png"/> 

- 💻 *Work Experience:* I have worked in Tata Consultancy Services and Informatica for 3 years as a Software Engineer .I have also interned as a web developer with IIIT Hyderabad ,Utkarshini and Javatpoint  <img align="center" height="30" src="https://img.icons8.com/emoji/48/000000/rocket-emji.png"/>


### 📌 Here's a link to my [Portfolio](https://aadhar54.netlify.app/)


### 📌 Contact Me :

[<img align="center" height="40" src="https://img.icons8.com/color/48/000000/hot-article.png"/>](https://hashnode.com/@aadhar54)
[<img align="center" height="40" src="https://img.icons8.com/color/144/000000/linkedin.png"/>](https://www.linkedin.com/in/thebtechviral/)
[<img align="center" height="40" src="https://img.icons8.com/fluent/144/000000/twitter.png"/>](https://twitter.com/aadhar54)
[<img align="center" height="40" src="https://img.icons8.com/fluent/144/000000/instagram-new.png"/>](https://aadhar54.github.io/)

[31/05, 08:07] aadhari🟡: Q2 check if duplicate present in group of 'distance' d number of elements. 
distance  = 3
1 2 3 1 4 5 1
false 

distance  = 3
8 9 1 4 6 7 6 
true

Try this using :
1. Brute Force
2. Sliding Window


"Q.1
k = 3
str = ""xyzzazb"" 
ans = 2 [xyz, azb]

k=3
str = ""cdfcghyxzazazb"" (testcase 2)

Return the count of substrings of size k where characters are not repeated."
// This is fixed sliding window

boolean isDuplicate(int[] arr, int distance) {
    int i = 0;
	
    Set<Integer> set = new HashSet<>();
	
    for(int k = 0; k < distance; k++) {
        if(set.contains(arr[k])) {
            return true;
        }
        set.add(arr[k]);
    }
	
    set.remove(arr[i++]);
	
    for(int k = distance; k < arr.len; k++) {
        if(set.contains(arr[k])) {
            return true;
        }
        set.add(arr[k]);
        set.remove(arr[i++]);
    }
    return false;
}

// FLEXIBLE SLIDING WINDOW

int countStr(String str, int k) {
    int count = 0;
    int start = 0;
    Set<Character> set = new HashSet<>();
    for(int end = 0; end < str.length(); end++) {
        while(set.contains(str.charAt(end)) && start < str.length()) {
            set.remove(str.charAt(start)); // window shrink from the left
            start++;
        }
        set.add(str.charAt(end)); // window expand from right
        (if(end - start + 1) == k) {
            count++;
        }
    }
    return count;
}
   

<br />
<br />

---

[website]: https://aadhar.bio.link/
[twitter]: https://twitter.com/aadhar54
[youtube]: https://www.youtube.com/c/AADHAR451
[instagram]: https://aadhar54.github.io/
[linkedin]: https://linkedin.com/in/thebtechviral/

# "There is only one thing more important than helping others is helping others to be able to help others ."

===========================================
What I am learning these days :
https://www.javaguides.net/2021/07/crud-junit-tests-for-spring-data-jpa.html
=======================================

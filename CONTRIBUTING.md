# Educative courses database
This comprises of data on courses assisting in learning technical subjects

## Procedure :
1. Fork this repository and edit as per the following rules.
2. Once the infomration is added and is in a proper structured format, create a pull request.
3. Wait for it to get merged !

### Rules:
1. ***platform*** name should be in **lowercase**
2. ***id*** is the number assigned by your mentor
3. ***module_number*** should be an **integer**
4. if modules are unavailable, videos, chapters etc can be added
5. ***free_courses*** - can have either **'yes'** or **'no'** against them
6. ***difficulty*** can be either one of three options- **'beginner'** , **'intermediate'** or **'expert'**.
7. ***certification*** can be either one of three options- **'free'** (for *free courses with free certifications*), **'paid'** (either for *paid courses* or *free courses with paid certifications* ) and **'none'**.
8. Make sure that the courses you're entering into the database don't already exist there !

### Reference :
You can take the reference from below example and structure your information similar to that.

   
  ```
  [
     {
       "id" :  1,
       "platform" : "educative",
       "free_course" : "no",
       "course_name" : "Accelerated Linux Core Dump Analysis",
       "link" : "https://www.educative.io/courses/accelerated-linux-core-dump-analysis",
       "difficulty" : "expert",
       "module_number" : 15,
       "certification" : "paid"
     },
     {
       "id" :  2,
       "platform" : "educative",
       "free_course" : "no",
       "course_name" : "Foundations of Linux ARM64: Debug, Disassemble, and Reverse",
       "link" : "https://www.educative.io/courses/foundations-of-linux-arm64-debug-disassemble-and-reverse",
       "difficulty" : "intermediate",
       "module_number" : 15,
       "certification" : "paid"
     }
]

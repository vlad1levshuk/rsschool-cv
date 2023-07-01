# [rsschool-cv](https://rs.school)
# Vladislav Levshuk

_______________

## **Contact information:**

**Phone:** +375 (33) 355-39-94

**E-Mail:** 3553994@gmail.com

_______________

## **Briefly About Myself:**

Hello! My name is Vlad, and I am currently a second-year student pursuing at BSUIR. I am passionate about programming, video and photo editing.

I believe in the power of continuous learning, and I am always eager to expand my knowledge and skills. I enjoy taking on challenges and approaching them with a positive and solution-oriented mindset. I am a team player and value collaboration, as I believe that working together can lead to innovative and successful outcomes.

In my free time, I like to spending time with loved ones, playing computer games, listen to music and watch movies or series. These activities not only provide me with relaxation but also contribute to my personal growth and creativity.

I am excited about the opportunities that lie ahead and look forward to further developing my skills and knowledge throughout my academic journey. I am open to new experiences and eager to make a positive impact both within the university community and beyond.

_______________

## **Skills and Proficiency:**
- Sony VEGAS
- Adobe Photoshop
- C++
- HTML5, CSS3
- JavaScript Basics
- Git, GitHub

_______________

## **Code example:**
**Two Sum from LeetCode:**
Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target. You may assume that each input would have exactly one solution, and you may not use the same element twice. You can return the answer in any order.

```C++
class Solution {
public:
     vector<int>twoSum(vector<int>& nums, int target) {

        vector<int> numbers;

        for (int i=0; i<nums.size();i++)
        { 
           for (int j=i+1; j<nums.size();j++)
            { 
                if( nums[i] + nums[j] == target )
                {
                   numbers.push_back(i);
                   numbers.push_back(j);
                   break;
                }
            }

        }

        return numbers;
    }
};

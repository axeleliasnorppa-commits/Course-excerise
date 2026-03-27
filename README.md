# Smart Study Planner

Building AI course project

## Summary

An AI tool that helps students plan study time efficiently by analyzing study habits and predicting performance. It provides personalized recommendations to improve learning outcomes and reduce stress.

## Background

* Students struggle with time management
* Inefficient study methods reduce performance
* Lack of feedback makes improvement difficult

## How is it used?

Students input study hours, subjects, and goals.  
The AI analyzes the data and suggests a personalized study plan while predicting performance.

Simple code example:
def predict_performance(hours):
# simple logistic-like function
import math
return 1 / (1 + math.exp(-0.1 * (hours - 50)))

print(predict_performance(70))
## Data sources and AI methods

* Data: study hours, grades, habits (self-reported or school data)
* Methods: logistic regression, basic recommendation system

## Challenges

* Data may be inaccurate
* Learning styles differ between students
* Privacy concerns with personal data

## What next?

* Develop into a mobile app
* Improve predictions using more real-world data
* Add real-time study tracking

## Acknowledgments

* Inspired by student productivity tools
* Created as part of the Building AI course

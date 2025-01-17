---
layout: post
title: Check Your Assumptions
subtitle: Researchers and Students Alike may Benefit from Revisiting the Statistics they Learned 
date: '2023-07-01 19:47:00 -08:00'
background: '/img/posts/erroneous.png'
full-width: true
---

<style type="text/css">
  p {
    width: 900px;
  }
</style>

## Introduction

During my many years tutoring statistics, many of my students were Ecology, Psychology or Social Sciences majors struggling to make it through their required basic Statistics courses. However, more often than not, I found my students weren't really learning statistics in their Statistics courses. Instead, they were learning a systematic algorithm to solve homework and test questions. When approached with a familiar problem, I discovered most of my clients simply identified the *type* of problem at hand and then followed a step-wise formula to the appropriate answer. For example, suppose a student is presented with sample data and asked to calculate the 95% confidence interval of the sample mean. Most students would identify this as a 'sample mean CI' type of question, and simply calculate the mean and variance to plug into a formula, where they arrive at the correct answer. 'A' leads to 'B' leads to 'C', etc, in this linear solution pathway. 

Although this somewhat algorithmic approach to Statistics homework and test problems is effective at guiding novice students to the correct solution space, the opportunity for generalizing these concepts to gain a deeper understanding of underlying notions is all but lost. In the example mentioned above, it is never asked *why* we used that particular formula, *how* confidence intervals work in other situations, and *what* assumptions are being made to even use these in the first place. Indeed, when presented with variations of familiar problems, the formulaic approach tends to fail to lead them to the answer. A big problem arises when these students become scientists with only basic Statistical education whom design and analyze their own experiments. In the real-world setting, many of the requirements and assumptions, previously taken for granted in their Introductory Statistics classes, fail to be satisfied, and conclusions made from these experiments are ultimately unfounded. 

All of this is not meant to criticize the knowledge of researchers or debase a university education. Instead, I intended this article to be a friendly reminder of what could go wrong if we do not appreciate a comprehensive understanding of the statistics used in research. 

## Parametric Tests

Any researcher likely uses many of the same statistical tests taught in and introductory statistics class. These may include a $z$-tests, $t$-tests, $F$-tests, and many other tests used to make inferences about a population from sampled data. What most may not immediately realize is that these are all *parametric* tests, meaning the validity of these tests rely heavily of sets of inherent assumptions about the distribution of the data. These assumptions usually always include **constant variance**, **independent observations**, **no outliers**, and most importantly, **Normal distribution**. In other words, some of the most common statistical tests used to make inference from experiments completely depend on assuming Normal *parameters* of the underlying population distribution from which we sampled. As mentioned, in many applied analysis situations, such as medical drug trials, we are often actually sampling from a population distribution that is far from Normal. Hence, our base-line assumption for parametric tests is violated and valid conclusions from the data cannot be drawn via these methods. 

Many researchers are very familiar with the Normal distribution, as it is ubiquitous in most undergraduate level statistics courses. However, few may recognize the nuance that the Normal distribution is really just a specific case of the general notion of a  *cumulative probability distribution*. 
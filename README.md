
# Kai's Portfolio

---

## Research Experience

### Algorithmic Game thoery:

1. Routing Games (**Routing Games with Priorities**: [AAAC 2016](http://aaac2016.ie.nthu.edu.tw/index.php/program/) oral presentation [**PowerPoint**](https://drive.google.com/open?id=0B4RZUg4dmHKabi1yQUxReWFuSmc))

  - I introduce priorities to routing games, which means people can choose different priorities and pay the corresponding additional payment in order to get the priorities.
  - With the priorities, players can be prior to other players with lower priorities. They only need to afford the traffic flow of higher or equal priorities.
  - Under this assumption, I found that the optimal total cost of the whole game can be computed by integration of the cost function. And the total cost of the Nash equilibrium is equal to the original routing game without priorities. 
  - That means we can have **an efficient way to compute the upper bound of the PoA (price of anarchy).** It will be: (total flow * unit cost) / integration of the cost function.
  - This can be generalized to arbitrary graphs, and the upper bound of the PoA (price of anarchy) will be bounded by the largest threshold of value computed by the above formula (we applied one of the theory in the Selfish Routing, Prof. Tim Roughgarden)
  - **A simple application is that if all of the cost function is a polynomial with degree less than d, then the PoA will be bounded by d+1.**

2. Network Formation Games

---

## Working Experience

### Machine Learning

1. Personalized Recommendation System (utilization of the following paper: https://datajobs.com/data-science-repo/Recommender-Systems-%5BNetflix%5D.pdf)

2. Mixerbox Radio Recommendation System (language detection of youtube videos)

### Backend and Frontend Development

1. Google Play Store Crawler

2. APIs for getting apps data of given appid

3. Elasticsearch for Chinese Article Search engine

4. Google Play Store History Visualization [**Demo**](http://ec2-35-167-141-110.us-west-2.compute.amazonaws.com/)

[![IMAGE ALT](https://github.com/b01901169/portfolio/blob/master/screenshot.png)](http://ec2-35-167-141-110.us-west-2.compute.amazonaws.com/)


---

## College Projects

1. Apply Reimforcement Learning to AI (Puyo Puyo, a game similar to the tetris battle)
  * [Gameplay vedio](https://www.youtube.com/watch?v=lLSFcXYhXMs) (Sorry that my arduino is broken, so currently I can't record and demonstrate the demo vedio of our AI.)
  
   [![IMAGE ALT TEXT](http://img.youtube.com/vi/lLSFcXYhXMs/0.jpg)](http://www.youtube.com/watch?v=lLSFcXYhXMs "Puyo Puyo Game")

  * Our AI can easily achieve 7 combos and defeat some of the official AIs.
  * Briefly introduce the concept we used:
    - We write a C++ code to capture the frames of the game and get the information of the current and next squares.
    - We set several features and its corresponding weight. According to the weighted sum, the AI can compute the best expected weighted sum using the Bayesian inference.
    - By playing with computer and the scores that we receive, the AI will learn from failures and adjust its weights. Then become a better AI.

2. Automatic Stage Simulator [**Demo**](https://youtu.be/nHz5ARB4QXg)

  * Use DE2-115 (Hardware implementation) to build a tempo detection
  
  [![IMAGE ALT TEXT](http://img.youtube.com/vi/nHz5ARB4QXg/0.jpg)](http://www.youtube.com/watch?v=nHz5ARB4QXg "Automatic Stage Simulator")
  
3. Bicycle Tuning Detection System [**Demo**](https://youtu.be/zKByzYzvFNQ?t=191)

  * Directly use EMG sensor to detect the signal of eyes and apply it to predict the behavior of drivers

  [![IMAGE ALT TEXT](http://img.youtube.com/vi/zKByzYzvFNQ/0.jpg)](https://youtu.be/zKByzYzvFNQ?t=191 "Bicycle Tuning Detection System")
  
  

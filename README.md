Question 1: In your opinion what are the 3 most important factors of a 12 factor app?
1.) dev-prod parity- flexibility of being able to push code at any time with minimal constraints. 
2.) port-binding - due to the security it offers by only exposing ports that are not open.
3.) Disposability - apps should minimize startup time and terminate gracefully

Question 2: Restate the Core Values of DevSecOps in your own words?
People over processes and tools: you value working face to face with us rather than sharing a recording. 
Automation: Devsecops relies on automation in order to make deliveries over a period of few hours, and make frequent deliveries across platforms.
Measurement: You can only improve what is measured. It allows you to see your current state and then look back at the progression with a future state.

Sharing: Value fast feedback loops and daily collaboration with our stakeholders to ensure we're building the right thing. 


Question 3: Which of the 3 ways of DevSecOps do you think is the most difficult to implement? Explain why?
The culture of continual experimentation and learning. Culture takes the longest change and you must have buy in from the top down. With that, it's not easy to convince leaders than you need to slow down to speed up. That delivery may stop for a period while you try something new. Failure is still heavily frowned upon at many organizations which is the crux of learning and experimentation. 
Question 4: Why are we encouraged to treat our services as disposable?
When we need to deploy a new version of the code, the old environment is destroyed and a new one is built exactly as the old one. This supports the idea of treating infrastructure as “cattle” (disposable) versus “pets” (keep around forever).

Question 5: Why is Dev Prod parity so important? What are some ways to acheive this?

It is important because we can then push code to production at any time. Want code environments to be as close to each other as possible.
Ways to achieve this: 
Keep development, staging, and production as similar as possible![image](https://user-images.githubusercontent.com/80227752/110261401-16cbe480-7f7e-11eb-8cef-b025f6ea625c.png)


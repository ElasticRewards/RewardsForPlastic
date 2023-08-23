# Rewards For Plastic

Selected Problem: Humans are humans. They skip sorting plastic waste. It gets lost and turns microplastic. How do we increase the rate of plastic recycling so people do not skip plastic waste recycling / sorting?

Solution: We pass plastic item acceptance & preliminary sorting to recycling machines. As close to humans as possible. People will be rewarded for doing good (not yet clear how), to keep them motivated long run. We start to build solution, where machines accept any plastic (as bottles & cans are accepted these days) and pre-sort them for further streaming into plastic recycling chain.

This project is 2nd pivot (project salvage) from original team pivoting into own delivery.

## **Work sequence and planning for next steps**

1. **Find hardware to make it demo possible outside normal laptops**
    1. Find Raspberry Pi (or similar SBC) - so it looks embeddable into real recycler [*] borrowed
    2. Find attachable small camera, as cheap and simple as possible on short time [*] borrowed
2. **Make optical object recognition viable**
    1. Dev strategy to cut on time to deliver optical object recognition - [*] HuggingFace
    2. Study datasets in public with plastics code in minimal variety, yet enough for ML training [*] Kaggle
    3. Work out available dataset to make feasible model training - SBC GPU is not fit, laptop GPU not fit [pivot]
    4. Tried external training HW with good GPU - finally [*]
    5. Use HuggingFace for choice of pre-trained models to cut dev time. [*] (sort of, needs better try later with TinyML)
    6. Try to detect **single** plastic object code in vision frame, at least one. [*]
    7. Try to detect plastic object code on few objects in frame. [*] sort of done, some ambiguity and delays
    8. Try to add more visible codes (different from existing) to make it working in realistic conditions - NOT achieved due to lack of time 
3. **What should be done next afterwards, we have more time**
    1. Look for realistic demo recycler hardware, or at least build plausible demo
    2. Make object labels produced near-real-time
    3. Make actuators reacting for object labels, so accepted item is mechanically sorted
    4. Find non-tech item: support from European dev agency.
    5. Work more on business model with initial stage(s) more as impact business model.
4. **Proejct description** 
    1. Inspiration 
    2. What it does
    3. How we built it
    4. Challenges we ran into
    5. Accomplishments that we're proud of
    6. What we learned
    7. What's next for Rewards For Plastic
       1. Find / salvage recycling point hardware in order to build true demo.
       Or make cute demo model.
       Current demo video speaks about microplastics challenge to keep people aware of challenge.
       2. Make said demo recycler recognize near 100% of thrown in objects.
       3. Build team, which is able to be more contingent and delivering, hopefully turning it into self-sustained business model
       4. Make aforementioned plan supported by one of European development agencies. Focus on impact business model in first stage(s)

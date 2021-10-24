# merquri-interview
Merquri Interview Test

Part A: Visual Representation
1. Tabs: Active state with left border style
2. Dialogs: Success with green tick
3. Selection: Radio button
4. Alignment: Checkbox aligned top with description
5. Choice: on/off switch
6. Placement: Continue button on top

Part B: Styling
1. https://github.com/jovinewong/merquri-interview/blob/main/question-b-1.html
2. https://github.com/jovinewong/merquri-interview/blob/main/question-b-2-3.html
3. https://github.com/jovinewong/merquri-interview/blob/main/question-b-2-3.html
4. https://github.com/jovinewong/merquri-interview/blob/main/question-b-4.html
   
   Three way I'd use to center align a box element:
   a. Flexbox
   b. Position absolute
   c. Margin 0 auto
   
Part C
1. New array with age > 28

   const newList = nameList.filter((e) => {
      return (e.age > 28)
   });
   
2. Total age

   const sum = newList.reduce((total, e) => total + e.age, 0);
   
3. New array

   let i,
      newArray = [];

    nameList.map((ele, i) => {
      if(nameList[i].occupation)
        newArray.push(nameList[i].name + "-" + nameList[i].occupation);
      else
        newArray.push(nameList[i].name);
    });
    
 4. Convert mockup to web: https://github.com/jovinewong/merquri2
    * Sorry that I'm unable to use any suggestion framework for the code but i use node js and donut generator for it. I'm trying my best to do it with the way I can do.
   

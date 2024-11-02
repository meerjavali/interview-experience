keka hr interview experience for the angular senior front end dev role.
--------------------------------------------------------------------
there are total 3 rounds.
1. coding round.
2. technical discussions.
3. hr round.

-----------------------------------------------------------------------
date 21-10-2024. time 4.30 pm to 6.30pm.

I was expecting the coding round be like solving a problem statement. like hacker rank or leet code challenge. i was surprised when 
interviewer asked me to connect to their VDI. he showed me a angular application with initial code. he asked to finish a task.

the task is 
there are 2 api's. 
1. movielist api(contains list of movie details like cast, title, id, poster, direction, duration,year)
2. movie details api(contains movie details based on movie id, cast, drection, review, title, etc..).

now task is to implement api integration.
1. on landing page i need to display all the movie's coming from first api (i.e movie list api)
in a card format. so each movie details will be display like a card format.
2. when user clicks on the movie card has to navigate to movie details page. 

styles were given. 


there were some restrictions
==> use good angular coding practices and code organizing
==>use strict typing and avoid "any" as type.


this task was easy to me thanks to a dear friend of mine. she developed similar project it is also availale in my repo's https://github.com/meerjavali/API-NgApp


i am able to complete the challenge on time.

key points
----------
1. i created interface's for response type. so that i can use them as model and avoid usage of any.
2. i used angular cli commands to create the componets, pipe
3. i used router concepts to navigate, registering routes
4. i created pipe because in response  duration is coming in minutes format so. eg. 127 it should be displayed as 2h 7 min.
    so quickly i created custom pipe 

i was doing all this sharing my screen. felt proud recollecting all the modules/syntax needed without google

i got a good feedback and promoted to second round.
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
2nd round was technical discussion
date 22-10-2024 and time 6pm to 7pm

actually I'm nervous before interview. i am at my office it was full of rain. i thought of early logout but it was raining till 5.30pm.
I'm nervous about the interview. i didn't want to take the interview for various personal reasons. on the other hand i don't want to accept failure. so at the last minute i reached my hostel and got ready for TR2

there was hi/hello. he asked me to take of my earphones and talk on laptop mic. directly. (felt little discomfort)

1. why are u looking for change?in the spain of 6 months.

	i felt very difficult to answer the question. (have told some real and unreal points. not expected this kind of question in TR)

2. tell me about your self?

	I have told about my intro. at the end i told him thank you. (he asked me why did u told thank you. we are not done yet na ?. idk why he didn't like. i said ok. and tried to be calm )

from now everything is technical
--------------------------------

3. change detection strategy in angular?
    
	I said i am unaware of this immediately. as idk never used any kind of this. he tried to give me hints like (onpush, default)

4. angular versions differences?

	able to answer with migration changes

4. lazyloading?
	
	I am able to answer this with good example. ( i got 2 questions from this related loadchildren, forchild)

5. dependency injection?

	i have explained DI using services example.

6. As i used services concept he asked how different service instance will be created.

        I have told him if we declare the service name in providers array at root module it will be one.
        if we declare in component level multiple instances will be created.

7. he said correct is there any other way for single instance he asked.

        i took time, and said currently i could recollect only this way. (then he asked me about what happens when service created in cli like a hint) then i have told him provideIn: root concept for single instance. he said good


8. he continued to ask how to inject services to component.

      i said using inject() method from angular library. he continued to ask any other way. i said i use constructor level injecting in regular practice. any how it doesn't impact how we inject.

he said ok.

9. he asked about forms , reactive forms?

     Able to answer all the questions (i got 4 questions here)

10. interface and model difference?
    
     able to answer this https://medium.com/@snehalv.2010/understanding-model-class-and-interface-in-angular-953e9fe668c0

11. he said i am done. any questions.

	I asked about feedback or suggestions. 

        he said it was good. u had good experience in angular. but he reminded it is good to implement change detection strategy. he said not aware of this concept is not good.


i said ok i will learn thank you...


---------------------------------------------------------------------------------------------------------------------------------------


my analysis it was 85% good interview for me. 


later day i got hr sorry mail. i didn't disappoint.

---------------------------------------------------------------------------------------------------------------------------------------


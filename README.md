# b4x20221230
B4X實驗: B4X BANano產生網站篇-BANano+BANanoElement(Umbrella JS)+JavaScript 製作一個PWA得CRUD,NON JQuery

B4X實驗: B4X BANano產生網站篇-BANano+BANanoElement(Umbrella JS)+JavaScript 製作一個PWA得CRUD,NON JQuery
參考資料:
https://www.b4x.com/android/forum/threads/banano-for-dummies-by-example.108722/page-2#posts

https://ithelp.ithome.com.tw/articles/10185638 外觀參考


0.Mashiane 製作了一個 BANano + Jquery 的網頁.功能是一個簡單的CRUD
Lesson 17: We showcase a task manager built with BANano + Jquery

This lesson is more about the logic and functionality than the UX / used libraries.

>>1. Add a task
>>2. Update a task
>>3. Delete a task
>>4. Move a task up
>>5. Move a task down
>>6. Save tasks to LocalStorage
>>7. Load tasks from LocalStorage
>>8. Adding buttons inside a list
>>9. Adding events to items before they get added to UX.
>>10. Detecting events on button clicks for elements without ids by using BANanoEvent


1.Mashiane 製作了一個 BANano + Jquery 的網頁.功能是一個簡單的CRUD

我把他的題目做一個修改.我不使用JQuery
希望使用BANano 原生的方法實踐 簡單的CRUD
BANano+BANanoElement(Umbrella JS)+JavaScript

因使用到javascript的focus,javascipt 所以暫時要用(等熟悉之後.看是否能少用javascript)
	Dim n1 As BANanoObject = BANano.Window.GetField("document").RunMethod("getElementById", Array("newtask"))
	n1.RunMethod("focus",Null)

目標: BANano+BANanoElement(Umbrella JS)  

2.須具備知識--B4X / Html/JavaScipt/Umbrella JS


3.看起來...用這種寫網頁.真的很快速.易懂!!!
不過.我還要深入測試




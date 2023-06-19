GitHub. HW_2
1. На локальном репозитории сделать ветки для: 
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
**git branch для вывода перечня веток и git branch название (из списка) для создания каждой новой ветки**
_
(вместо пробела нужно прописывать _ иначе выдаст уведомление об ошибке)_

2. Запушить все ветки на внешний репозиторий **git push -u origin --all**
  
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта **cat>bugreport.txt и CTRL+C**
  
4. Запушить структуру багрепорта на внешний репозиторий **git add . git commit -m “комментарий” git push**
  
5. Вмержить ветку Bag Reports в Main git checkout main для переключения ветки куда будет добавляться другая и затем прописать **git merge BugReports**
  
6. Запушить main на внешний репозиторий. **git push -u origin main**
  
7. В ветке CheckLists набросать структуру чек листа.
**git checkout CheckLists** 
 **cat>checklist.txt и CTRL+C**

8. Запушить структуру на внешний репозиторий 
**git add . 
git commit – m “комментарий” 
git push -u origin CheckLists**

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main через веб-интерфейс гитхаба на сайте результат «Pull request successfully merged and closed»
  
10. Синхронизировать Внешнюю и Локальную ветки Main 
**git checkout main
git pull**

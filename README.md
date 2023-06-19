GitHub. HW_2
1. На локальном репозитории сделать ветки для: git branch для вывода перечня веток и git branch название для создания новой ветки
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing

2. Запушить все ветки на внешний репозиторий git push -u origin --all
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта cat>bugreport.txt и CTRL+C
4. Запушить структуру багрепорта на внешний репозиторий git push -u origin BugReport
5. Вмержить ветку Bag Reports в Main git checkout main для переключения ветки куда будет добавляться другая и git merge BugReports 
6. Запушить main на внешний репозиторий. git push -u origin main
7. В ветке CheckLists набросать структуру чек листа. cat>checklist.txt и CTRL+C
8. Запушить структуру на внешний репозиторий git push -u origin CheckLists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main через веб-интерфейс гитхаба на сайте результат «Pull request successfully merged and closed»
10. Синхронизировать Внешнюю и Локальную ветки Main git pull

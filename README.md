# GIT_HW2
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
git branch
2. Запушить все ветки на внешний репозиторий - git push -u origin
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта - git checkout bug_reports => vim bug_report.txt
4. Запушить структуру багрепорта на внешний репозиторий - git add bug_report.txt => git commit -m "add bug_report.txt" => git push
5. Вмержить ветку Bag Reports в Main - git checkout main => git merge bug_reports
6. Запушить main на внешний репозиторий. - git push -u origign main
7. В ветке CheckLists набросать структуру чек листа. - git checkout checklists => vim checklist.txt
8. Запушить структуру на внешний репозиторий - git add checklist.txt => git commit -m "add checklist.txt" => git push
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main - Compare & pull request => Create pull request => Merge pull request => Confirm merge
10. Синхронизировать Внешнюю и Локальную ветки Main - git checkout main => git pull

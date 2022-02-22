# GitHub. HW_2 :white_check_mark:
1. На локальном репозитории сделать ветки для:
- Postman `$git branch Postman`
- Jmeter		`$git branch Jmeter`
- CheckLists	`$git branch CheckLists`
- Bag Reports	`$git branch Bug_reports`
- SQL			`$git branch SQL`
- Charles		`$git branch Charles`
- Mobile testing	`$git branch Mobile_testing`

2. Запушить все ветки на внешний репозиторий  
>$git add .  
>$git commit -m "New_brunch"  
>$git push  
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта  
>$git checkout Bug_reports  
>$vim Bug_reports.txt  
>>press i (INSERT)  
>>Hi folks!  
>>Here is some type of typical structure of Bug_reports  
>>*Bug ID  
>>*Bug summary  
>>*Bug Details  
>>*Bug Priority  
>>*Bug Description  
>>*Some attachments to the Bug Report  
>>press Esc; type :wq  
4. Запушить структуру багрепорта на внешний репозиторий  
>$git add Bug_reports.txt  
>$git commit -m "Struckture_of_bug_report"  
>$git push  
5. Вмержить ветку Bag Reports в Main  
>$git checkout main  
>$git merge Bug_reports  
6. Запушить main на внешний репозиторий.  
>$git add .  
>$git commit -m "merge of bug_reports"  
>$git push  
7. В ветке CheckLists набросать структуру чек листа.  
>$git chekout CheckLists  
>$vim Checklist.txt  
>>Insert  
>>Minimim for the check_list  
>>ID  
>>Tester action  
>>Actual result  
>> also if needed we can add Comment line  
>>Esc  
>>:wq  
8. Запушить структуру на внешний репозиторий  
>$git add CheckList.txt  
>$git commit -m "CheckList structure"  
>$git push --set-upstream origin CheckLists
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main  
>in GitHub click on "brunches", choose "CheckLists" brunch,click on "Compare& pull request", create pull request  
10. Синхронизировать Внешнюю и Локальную ветки Main  
>$git fetch

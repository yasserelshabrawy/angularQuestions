# angularQuestions

Component Life Cycle ??
1- constractour
2-ngOnChanges :  بتشتفل عند حدوث اي تغيير في ال @input
3-ngOnInit  : بتشتغل مرة واحدة وهيا عند فتح الكمبوننت 
4-ngDoCheck : بتشتغل عند كل تغغير بيحصل في الكمبوننت وحتى لو محصلش تغيير في @Input
5-ngAfterContentInit : بتشتغل لما بستخدم ng-content 
6-ngAfterContentChecked : لما بيحصل تغيير في قيمة ng-content
7-ngAfterViewInit : بتشتغل لما بيتم عرض جميع العناصر بما فيهم DOM
8-ngAfterViewChecked : بتشتغل بعد كل عملية فحص ع العناصر كلها 
9-ngOnDestroy : بتشتغل لما باجي اقفل ال DOM
/////////////////////////////////////////////////////////////////////////////////////////////////

Observations noted:
-To satisfy the testing around the deletion of lists, I had to use a blank RedirectToAction which causes the website to crash. While each test case was satisfied (as is the direction of the exam), the application remains broken from a user experience standpoint (even though the list deletion does function properly). I left my notes and a commented section of code that should be used in ListControllers.cs lines 58-60. 

- Variable naming conventions could be more explicit. For example, there were instances where I was confused to which Id I was working with especially around the deletedItem functionality where I got the itemId and listId (displayed as Id) mixed up.

- All tests only covered positive results. Comprehensive testing would also include negative testing to ensure the system catches and fails properly.

- Not all labels were translating to French. Examples being "MyTodoLists" title, "Home" in the breadcrumbs, and "Changes saved successfully" in the status.
http://grepcode.com/snapshot/repository.grepcode.com/java/ext/com.jetbrains/intellij-idea/13.0.0/

https://github.com/JetBrains/intellij-community/blob/master/plugins/tasks/tasks-core/src/com/intellij/tasks/trello/TrelloTask.java

https://www.jetbrains.com/idea/help/preparing-plugins-for-publishing.html


https://tfs-task-integration.googlecode.com/svn/trunk/src/task/TFSRepository.java


POST: https://nhahv.visualstudio.com/DefaultCollection/ClipHaiTV/_apis/wit/wiql/?api-version=1.0

{
  "query": "Select [System.Id], [System.Title], [System.State], [System.WorkItemType] From WorkItems Where [System.TeamProject] ='ClipHaiTV' AND [State] <> 'Closed' AND [State] <> 'Removed' order by [Microsoft.VSTS.Common.Priority] asc, [System.CreatedDate] desc"
}

GET https://nhahv.visualstudio.com/DefaultCollection/ClipHaiTV/_apis/wit/queries/Shared%20Queries/Task and Context?api-version=1.0

https://nhahv.visualstudio.com/DefaultCollection/_apis/wit/workItems/5
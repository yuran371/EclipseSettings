Sharing eclipse specific settings across workspaces:

Go to {old Workspace}/.metadata/.plugins/org.eclipse.core.runtime/.settings


Copy everything under the above directory: {new Workspace}/.metadata/.plugins/org.eclipse.core.runtime/.settings

This is going to make sure that the ${new_workspace} is having the same configuration as the ${old_workspace}

Update in case of any issues.


https://stackoverflow.com/questions/2078476/how-to-share-eclipse-configuration-over-different-workspaces

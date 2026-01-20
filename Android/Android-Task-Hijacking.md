### It is also known as **StrandHogg**
#### In this file we will understand about Android Task Hijacking, Reports & Articles.

##### https://blog.takemyhand.xyz/2021/02/android-task-hijacking-with.html

##### Part 1 - https://redfoxsec.com/blog/task-hijacking-strandhogg-part1/
##### Part 2 - https://redfoxsec.com/blog/task-hijacking-strandhogg-part-2/

• Activities: There are four activities in the app MainActivity as the root activity, and LoginActivity, DashboardActivity, and SettingsActivity as other activities.

• Task: These activities together form a task, and as the user navigates through them.

• Back Stack: The back stack stores the history of these activities, allowing the user to navigate back through the task.

#### How to identify if application is Vulnerable to Task Hijacking?
1. Launch Mode is android:launchMode=”singleTask”
2. Minimum SDK Version < 30 (Android 11) (app may not have protections against task hijacking bugs)

There are two types StrandHogg 1.0 and StrandHogg 2.0
strandHogg 2.0 is having CVE CVE-2020-0096 and is advanced and more critical and complex version of Android Task Hijacking


#### Task Hijacking (StrandHogg 1.0)
1. https://www.helpnetsecurity.com/2019/12/03/strandhogg-vulnerability/


#### StrandHogg 2.0 (CVE-2020-0096)
1. https://www.helpnetsecurity.com/2020/05/28/cve-2020-0096/

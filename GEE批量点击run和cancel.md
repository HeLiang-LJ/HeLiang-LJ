- š Hi, Iām @HeLiang-LJ
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
HeLiang-LJ/HeLiang-LJ is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

RUN
function runTaskList() {
    var tasklist = document.getElementsByClassName('awaiting-user-config');
    for (var i = 0; i < tasklist.length; i++)
        tasklist[i].children[2].click();
}
function confirmAll() {
    var ok = document.getElementsByClassName('goog-buttonset-default goog-buttonset-action');
    for (var i = 0; i < ok.length; i++)
        ok[i].click();
}
runTaskList();
confirmAll();

CANCEL
function runTaskList() {
    var tasklist = document.getElementsByClassName('indicator');
    for (var i = 0; i < tasklist.length; i++)
        tasklist[i].click();
}
 
function confirmAll() {
    var ok = document.getE

$ vi readme1.txt

$ git diff
warning: LF will be replaced by CRLF in readme1.txt.
The file will have its original line endings in your working directory
diff --git a/readme1.txt b/readme1.txt
index 1c2fe06..de61948 100644
--- a/readme1.txt
+++ b/readme1.txt
@@ -1,3 +1,2 @@
-first line
-second line
+this is the first line

$ vi readme2.txt

$ git diff
warning: LF will be replaced by CRLF in readme2.txt.
The file will have its original line endings in your working directory
diff --git a/readme2.txt b/readme2.txt
index 1c2fe06..d3e2104 100644
--- a/readme2.txt
+++ b/readme2.txt
@@ -1,3 +1 @@
-first line
-second line
+This is the first line

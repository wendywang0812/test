#HCL NOTES開發規範
1. '.lss'檔案(Code/ScriptLibraries/):核心任務邏輯100%寫在'.lss'檔中。
2. '.lsa'檔案(Code/Agents/):修改時絕不可以動到XML結構，只修改<lotusscript>區塊。
3. 自動Git控管：當我要求"提交"時，請自動執行'git add.'、'git commit'與'git push'。
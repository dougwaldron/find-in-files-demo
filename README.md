The repository is only here to help demonstrate [this Visual Studio bug](https://developercommunity.visualstudio.com/t/Find-in-Files-and-Go-To-File-are-broken/1654445). The files in the attachments directory were attached to the bug report and demonstrate the bug. The original bug report:

> The “Find in Files” tool with “Look in” set to “Entire solution” or “Current project” does not seem to know where to look. It results in **zero total files searched**. Repeating the same search instead with “Look in” set to the folder where the solution is located will return all expected search results.
> 
> This is a new computer with a fresh install of VS 2022, installed using winget.
> 
> The issue occurs with some solutions but not all, but I can replicate the issue with a fresh clone of this repository (which is nothing more than a new console project containing four files): https://github.com/dougwaldron/find-in-files-demo
> 
> I’ve disabled **every** extension, including those that came pre-installed with VS, and I reset all VS settings using the import/export wizard.
> 
> I’ve attached a screen recording demonstrating the issue plus a screenshot of the search results panel showing “Total files searched: 0”.
> 
> Bonus: Go To File is also broken. This is also demonstrated in the screen recording.
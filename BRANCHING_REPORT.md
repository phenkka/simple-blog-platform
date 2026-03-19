# Branching Report

## Merge Statistics
- Total number of merges: [count]
- Fast-forward merges: [count]
- 3-way merges: [count]
- Merges with conflicts: [count]

## Branch History
git log --graph --oneline --all
* de48c85 (HEAD -> master, origin/master) Add BRANCHING_REPORT.md
*   0fe045e Merge branch 'documentation'
|\  
| * 6bfd9d6 (origin/documentation, documentation) Add documentatiton
|/  
*   23cc8d4 Merge feature/header-update with conflict resolution
|\  
| * aa992b8 Update header to v2.0
* | 8754539 Customize blog title
|/  
*   9b0fd6f Merge branch 'feature/design'
|\  
| * d1fd270 Improve design and add navigation
* | eae4429 Add comments section
|/  
* 1f5929f Add posts page and functionality
* bab1b2d nitial project setup

## Lessons Learned
В ходе выполнения задания я понял, что ветвление в Git — это мощный инструмент для изоляции работы. Разработчики могут одновременно создавать новые функции (как comments и design), не мешая друг другу и не ломая стабильную версию в main. Слияние (merge) объединяет эти изолированные миры, а возникновение конфликтов — это не ошибка, а естественный процесс, когда несколько человек меняют одни и те же строки кода. Главный навык — не бояться конфликтов, а аккуратно их разрешать, вручную собирая финальный, рабочий вариант.

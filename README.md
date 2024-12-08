<div style="background-color: #40E0D0; padding: 20px; font-family: Arial, sans-serif;">

# <span style="font-size: 2.5em;">GitHub қолдану бойынша қысқаша нұсқаулық</span>

## <span style="font-size: 2em;">1. Тіркеу және орнату</span>
- [GitHub](https://github.com) сайтында тіркеліңіз.
- Git ([git-scm.com](https://git-scm.com/)) орнатыңыз және атау мен электрондық поштаны конфигурациялаңыз:  
  `(git config --global user.name "Сіздің атыңыз")`  
  `(git config --global user.email "YourEmail@example.com")`

## <span style="font-size: 2em;">2. Репозиторий жасау</span>
- GitHub сайтында **Жаңа репозиторий** түймесін басыңыз.
- Репозиторийдің атын көрсетіңіз және **Репозиторий жасау** түймесін басыңыз.

## <span style="font-size: 2em;">3. Репозиторийді клондау</span>
- Репозиторий сілтемесін көшіріп, пәрменді орындаңыз:  
  `(git clone https://github.com/username/repository.git)`

## <span style="font-size: 2em;">4. Файлдармен жұмыс</span>
- Жоба қалтасында файлды жасаңыз немесе өңдеңіз.
- Файлды индекске қосыңыз: `(git add file_name)`
- Міндеттеме жасаңыз: `(git commit -m "Commit message")`
- GitHub-қа өзгертулерді басыңыз: `(git push origin main)`

## <span style="font-size: 2em;">5. Жергілікті репозиторийді жаңарту</span>
- Қашықтағы репозиторийден соңғы өзгерістерді алыңыз: `(git pull origin main)`

---

### <span style="font-size: 1.8em;">Код мысалдары</span>

**Репозиторийді клондау**  
`(git clone https://github.com/username/repository.git)`

**Файлды жасаңыз және оны репозиторийге қосыңыз**  
`("Hello, GitHub!" > hello.txt жаңғырығы)`  
`(git add hello.txt)`  
`(git commit -m "Қосылған hello.txt файлы")`  
`(git push origin main)`

**Python тілінде бағдарлама құру**  
`(echo 'print("Hello, GitHub!")' > hello.py)`  
`(git add hello.py)`  
`(git commit -m «Hello.py файлы қосылды»)`  
`(git push origin main)`

**Серверден жаңартуларды алу**  
`(git pull origin main)`

</div>

# "Laguna" Theme
* **Laguna Theme for Emacs**

![image](https://user-images.githubusercontent.com/5169660/148678108-7bf5a481-0b86-4c64-ab30-30ce250f3f06.png)


*([Magit](https://magit.vc/) support)*:
*This screenshot's an earlier version of the Laguna Theme.*
![screenshot](https://raw.githubusercontent.com/HenryNewcomer/laguna-theme/master/images/2020-09-29-magit.png)


**Laguna** is my personal emacs theme. It can be yours, too.


**Installation:**
  Laguna Theme is on MELPA. Please verify that MELPA has been added to your package archives.
```
      (load-theme 'laguna t t)
      (enable-theme 'laguna)
      ;; Or, if you use `use-package', do something like this:
      (use-package laguna-theme
        :init (progn (load-theme 'laguna t t))
        :defer t
        :ensure t)
 ```
**Terminal Colors look wonky in your terminal? This can sometimes helps:**
 ```
     # Throw this in your ~/.bash_profile if Laguna Theme (emacs) isn't displaying properly
     export TERM="xterm-256color"
 ```

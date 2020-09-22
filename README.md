# "Laguna" Theme  
* **Laguna Theme for Emacs**  
  
![screenshot](https://raw.githubusercontent.com/HenryNewcomer/laguna-theme/master/images/2020-09-22.png)  
  
**Description:**  
  - Full colored GUI; 256 color terminal support.  
  
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
**Terminal Colors look wonky? See if this helps:**  
 ```
     # throw this in your ~/.bash_profile  
     export TERM="xterm-256color"  
 ``` 

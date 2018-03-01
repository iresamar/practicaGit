# Práctica GIT

### Sanz Martín, Irene


--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset  --hard HEAD~1` 

Porque este comando borra lo último añadido dentro del working copy

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog ; git reset --hard f55fa7a` 

git reflog muestra todas la direcciones y pasos que hemos realizado y con git reset conseguimos volver al paso anterior

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No hubo conflicto porque la información estaba ya dentro de master, indicando "Already up to date."

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Sí hubo conflicto debido a la modificación del texto anteriormente.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No da ningún conflicto dado que se ha hecho el merge con fast forward. La rama master y styled comparten el mismo commit y no hay ramificaciones por lo que master absorbe todos los commits de la rama styled.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph` 

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

`git merge --no-ff title` 

 Si, puesto que estamos en la misma lista de ramas no perdemos ningún commit de title ya que lo absorbe master.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout --don-quijote.md` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title`

--  

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` `git reset --hard d0914eb`

--

**12. ¿Qué comando o comandos usaste en el paso 32?**

`git reflog` `git reset --hard c1131e6`

--

**13. ¿Qué comando o comandos usaste en el punto 33?**

`git reflog` `git reset --hard d0914eb`

--


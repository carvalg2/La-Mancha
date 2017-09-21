# Práctica GIT

### Vallet García, Carlos

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque así deshago el commit y lo que hay en el working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` y `git reset --hard e47a8d4`

Uso el primer comando para obtener el identificador del commit deshecho. Seguidamente, uso el segundo comando para llevar el puntero master y HEAD al commit deseado, modificando el Working copy.

--

**3. El merge del paso 13, ¿Causó algún conﬂicto? ¿Por qué?**

No, no causó ningun conflicto ya que el contenido del archivo don-quijote.md no colisiona con ningun otro.

--

**4. El merge del paso 19, ¿Causó algún conﬂicto? ¿Por qué?**

Sí, sí causó un conflicto debido a que el contenido del archivo don-quijote.md era diferente tanto en la rama styled y htmlify, impidiendo así que se formulase el merge hasta ser resuelto este problema.

--

**5. El merge del paso 21, ¿Causó algún conﬂicto? ¿Por qué?**

No, no causó ningun conflicto debido a que ambas ramas compartían mismo contenido debido al merge anterior del paso 13.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph` 

--

**7. El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?**

Sí, aunque obtendriamos unicamente un flujo de trabajo lineal.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1` 

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout -- don-quijote` 

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -D title` 

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reflog` y `git checkout 6de9a6d`

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reflog` y `git checkout 8648a28`

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reflog` y `git checkout c7597e0`

--
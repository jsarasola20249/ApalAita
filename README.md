# Apal — papá

La cáscara ya está lista. En la reunión solo hay que pegar un ID.

## Qué sustituir

En `index.html`, busca esta línea:

```text
PONER_AQUI_EL_ID_DEL_PROYECTO
```

Sustitúyela por el ID de la **Web App** de su Apps Script: el tramo de la URL que va entre `/macros/s/` y `/exec`. Empieza por `AKfycb`.

La línea tiene que quedar así:

```text
src="https://script.google.com/macros/s/AKfycb.../exec"
```

Ese ID sale en **Implementar → Administrar implementaciones**, en la URL de la aplicación web. El ID del engranaje (empieza por `1`) no vale aquí.

## Después de pegarlo

1. Commit en este repo.
2. Espera uno o dos minutos.
3. En su móvil, Chrome: https://jsarasola20249.github.io/appalpapa/
4. Menú → **Instalar app**.

El icono es «apal» y el nombre debajo es **Apal**.

### Sprawdzanie podatności na zagrożenia w stopniu krytycznym lub wysokim:
```
docker scout quickview --platform linux/amd64 s96504/lab:classic
```

![image](https://github.com/MykhailoKrylov/lab8/assets/134151663/172082ad-b5dd-44f7-be0d-7955d4687685)

### Pełną analizę CVE
```
docker scout cves s96504/lab:classic
```
![image](https://github.com/MykhailoKrylov/lab8/assets/134151663/2afa5708-5257-48af-9204-1b660d7d6222)

Po zaktualizowaniu zależności otrzymałem następujący wynik:
![image](https://github.com/MykhailoKrylov/lab8/assets/134151663/3badeab9-241e-4c6b-a4dc-4c91c75f62d6)

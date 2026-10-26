# Борис Горелик
# Домашнее задание к занятию 4 «Оркестрация группой Docker контейнеров на примере Docker Compose»

## Задание 1
https://hub.docker.com/repository/docker/borisgorelik171171/custom-nginx/general

## Задание 2
<img width="1908" height="1656" alt="Снимок1" src="https://github.com/user-attachments/assets/50845409-ba5f-48b4-ac8d-4ced22df4c99" />

## Задание 3
<img width="2209" height="1606" alt="Снимок2" src="https://github.com/user-attachments/assets/7a9a54aa-8166-4aa6-bf9c-faca03159a3a" />

<img width="1307" height="751" alt="Снимок3" src="https://github.com/user-attachments/assets/d52e2fbf-e4bf-427b-9fcd-54f648a74c4d" />

<img width="2229" height="387" alt="Снимок4" src="https://github.com/user-attachments/assets/40e5f5af-7907-42f8-9f8a-adba817418b5" />

## Задание 4
<img width="1575" height="999" alt="Снимок5" src="https://github.com/user-attachments/assets/cbca8c43-76b0-4553-aea2-67dda411d42b" />

<img width="1230" height="1635" alt="Снимок6" src="https://github.com/user-attachments/assets/aec53f7c-3566-4f49-84e8-34d91f19f529" />

## Задание 5
<img width="2220" height="1203" alt="Снимок7" src="https://github.com/user-attachments/assets/a071a206-f79f-43fe-b312-234a6db162b4" />

<img width="2553" height="1435" alt="Снимок8" src="https://github.com/user-attachments/assets/86b0830a-3c93-47d4-a372-02f9ab72eeb3" />

<img width="1422" height="526" alt="Снимок9" src="https://github.com/user-attachments/assets/26d8c699-4986-43c9-b413-d5c9314fed0c" />

<img width="3431" height="508" alt="Снимок10" src="https://github.com/user-attachments/assets/9ca797a4-7d90-42eb-9a24-42a335b94b58" />

<img width="1172" height="1489" alt="Снимок11" src="https://github.com/user-attachments/assets/3fa5f81b-a316-479d-8be5-7695e1599d66" />

<img width="2927" height="931" alt="Снимок12" src="https://github.com/user-attachments/assets/16391bd6-9eae-493a-a923-6fdebc8d49fa" />

При наличии обоих файлов Compose выбрал compose.yaml, поскольку это приоритетное имя конфигурации. Для подключения docker-compose.yaml использован include. После удаления compose.yaml сервис Portainer исчез из актуальной конфигурации, но его контейнер сохранился, поэтому Compose сообщил об orphan-контейнере. Флаг --remove-orphans удалил этот контейнер. Проект task5 завершён одной командой docker compose down --remove-orphans.




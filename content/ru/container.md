---
title: Контейнер
status: Completed
category: technology
tags: ["application", "fundamental", ""]
---

Контейнер — это запущенный процесс, работающий под управлением операционной системы компьютера, ограниченный в ресурсах и возможностях. 
Файлы, доступные такому процессу, упаковываются в так называемый образ контейнера.
Контейнеры работают рядом друг с другом на одной и той же машине, 
при этом операционная система, как правило, не позволяет контейнерам напрямую взаимодействовать.

## Какую проблему решает

До появления контейнеров для запуска приложений требовались отдельные машины.
На каждой машине устанавливалась операционная система, которая потребляла ресурсы процессора и памяти, а также дисковое пространство 
— и все это для работы одного единственного приложения.
Кроме того, приходилось тратить значительные ресурсы на обслуживание, обновление и запуск самой операционной системы.

## Как именно решает проблему

Контейнеры совместно используют одну и ту же операционную систему и работающее под ее управлением железо. 
Другими словами, вместо множества копий ОС используется лишь одна:
ресурсы, потребляемые операционной системой, делятся сразу на множество контейнеров. 
Тем самым обеспечивается эффективное использование памяти, процессора и дискового пространства.
Такая совместная работа контейнеров возможна только потому, что они, как правило, не могут напрямую взаимодействовать.
Это позволяет запускать на одной физической машине гораздо больше приложений.

Однако есть и ограничения.
Подход, когда множество контейнеров используют одну и ту же операционную систему, потенциально более опасен, чем другие варианты.
Кроме того, контейнерам необходимо задавать ограничения на использование общих ресурсов.
Администратор должен ограничивать использование памяти и процессора — это позволяет гарантировать, что остальные приложения не столкнутся с нехваткой ресурсов.

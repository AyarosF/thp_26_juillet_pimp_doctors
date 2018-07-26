# Pimp des docteurs - projet THP 25 juillet 2018

## Après avoir cloné le repo

Pour créer une BDD, faire :
- `bundle install`
- `rails db:migrate`
- `rails db:seed`

## Le contenu

A été créée une base de données, avec une application rails, en utilisant la gem ActiveRecord.

### Le projet

Une plateforme concurrente de Doctolib

- Un appointment ne peut avoir qu'un seul doctor, mais un doctor peut avoir plusieurs appointment
- Un appointment ne peut avoir qu'un seul patient, mais un patient peut avoir plusieurs appointment
- Un doctor peut avoir plusieurs patient, au travers des appointments, et vice versa
- Un docteur, un patient, et un rendez-vous appartiennent tous à une city
- Une city peut avoir plusieurs docteurs, patients, et rendez-vous
- Un docteur a plusieurs specialty et une specialty peut concerner plusieurs doctor


## La team

Ce programme est made in Strasbourg, by Soraya FRUCTUOSO, Samaneh VAEZI et Hugo PAYET avec amour ! Bonne correction les amis :kissing_heart:

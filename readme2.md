1. Contare quanti iscritti ci sono stati ogni anno

# SELECT YEAR(`enrolment_date`) AS 'annualità', COUNT(\*) AS 'numero_iscritti' FROM `students` GROUP BY YEAR (`enrolment_date`);

2. Contare gli insegnanti che hanno l'ufficio nello stesso edificio

# SELECT `office_number`, COUNT(\*) FROM `teachers` GROUP BY `office_number`;

3. Calcolare la media dei voti di ogni appello d'esame

#

4. Contare quanti corsi di laurea ci sono per ogni dipartimento

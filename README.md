# Recommendation-System-Using-Memory-Based-Collaborative-Filtering-Techniques
Project for the elective course of Scientific Computation (Master's Degree Program at the Faculty of Mathematics).


Projekat za izborni kurs Naučno izračunavanje na master studijama na Matematičkom fakultetu.

**Opis projekta:**

Cilj ovog projekta je implementacija sistema za preporuku filmova zasnovanog na uzajamnom filtriranju, koristeći algoritam KNN. Demonstrirani su različiti pristupi u predviđanju ocena - user-based i item-based, različiti pristupi za podelu skupa podataka na skupove za treniranje i testiranje - prebacivanjem dela ocena iz trening skupa u test skup i stratifikovana podela, različite mere sličnosti - kosinusna sličnost, Džakardova sličnost (još neke sličnosti su opisane u uvodnom delu), nalaženje vrednosti parametra k za koje je greška u predviđanju ocena najmanja, računanje RMSE, odziva, preciznosti i f1 mere.

**Opis korišćenog skupa podataka:**

Korišćen je MovieLens skup podataka. Ovaj skup sadrzi četiri tabele:
1) tabela movies sadrži kolone movieId, title i genres
2) tabela ratings sadrži kolone userId, movieId, rating i timestamp
3) tabela tags sadrži kolone userId, movieId, tag i timestamp
4) tabela links sadrži kolone movieId, imdbid i tmdbid

Za ovaj projekat od značaja je da svaki korisnik ima svoj ID i da svaki film ima svoj ID, kao i ocena kojom je korisnik sa određenim ID-em ocenio film koji ima dati ID. Takođe, korišćene su samo tabele movies i ratings.

**Korišćena literatura:**

1) Ricci, F., Rokach, L., & Shapira, B. (2011). Introduction to recommender systems handbook. In Recommender systems handbook (pp. 1-35). Springer, Boston, MA.
2) A.Mojdeh Bahadorpour, B.Behzad Soleimani Neysiani, C.Mohammad Nadimi Shahraki. Determining Optimal Number of Neighbors in Item-based kNN Collaborative Filtering Algorithm for Learning Preferences of New Users - https://core.ac.uk/download/pdf/229273663.pdf

Jovana Pejkić

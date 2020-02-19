Utöver programmet behöver du ha MySQL installerat på din dator.
Localhost ska vara ställd till defaultporten för MySQL och root måste kunna logga in i MySQL med lösenord.

För att testerna skall köras behöver du antingen ändra roots inlog till MySQL till vårt defaultlösenord: "my-secret-pw".
Annars får du gå in i teserna och ändra parametern till konstruktorerna som körs innan testerna till ditt eget lösenord.

För att köra programmet i Eclipse behöver du importera det som ett maven-projekt och sedan köra det.
För att köra programmet ifrån teminalen så behöver du ha java och maven installerat.
Kör sedan kommandot mvn package assembly:single och lägg därefter jar-filerna på classpathen när du kör java:
java -cp ContactBook-1.0-SNAPSHOT-jar-with-dependencies.jar:ContactBook-1.0-SNAPSHOT.jar cizero.domain.Main


HEJ HEJ J ALÖKJSGOIjajsoigjsaoigjsoiajgijdsag

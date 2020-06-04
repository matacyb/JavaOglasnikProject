# JavaOglasnikProject (In Process)

Upute za pokretanje aplikacije (Koristeći Eclipse IDE)

1. Otići na navedenu stranicu i skinuti "JavaFX Windows x64 SDK ver 14.0.1." https://gluonhq.com/products/javafx/  
2. Otvoriti projekt u Eclipse-u. Desni klik na folder projekta unutar Eclipse-a /Run As/Run Configurations
3. Odabrati Arguments tab te pod VM Arguments C/P sljedeće bez navodnika
"--module-path "C:\Users\#\Desktop\javafx-sdk-14.0.1\lib" --add-modules 
javafx.controls,javafx.fxml"
4. Putanja treba voditi do lib foldera unutar javafx-sdk (ono što ste skinuli iz koraka jedan).
5. Zatim unutar foldera projekta idemo do Main.java file-a na sljedeći način ->
  src/application/Main.java
6. Desnik klik na Main.java / Run As/ Java Application
7. To bi trebalo biti to. 

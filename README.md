# GeneratorMapBuild
Sterowanie:  
wasd - poruszanie się  
scroll - przybliżanie i oddalanie  

Width i height - całkowity rozmiar mapy  
OffsetX i offsetY - przesunięcie od punktu zerowego  
Scale - przybliżenie mapy  
Seed - seed aktualnie wybranej fali  

Przyciski:  

color - zmienia mapę na tryb czarno biały lub kolorowy  
suwak nad przyciskiem zmienia próg zmiany koloru zielonego na niebieski  

wybierz kolejną falę - zmienia aktualnie edytowaną falę  
dla każdej fali można zmienić frequency, amplitude i seed  
fala to jakby kolejna warstwa noiseMapy, tutaj ustawiłem że są dwie warstwy

losuj wartości fali - przypisuje losowe wartości dla aktualnie wybranej fali  

regeneruj - regeneruje mapę  


Uwagi:  
Frequency z tego co widze najlepiej wyglada jak jest < 0.15  
Amplitude zwiększa/zmniejsza wpływ danej fali na wynik końcowy  

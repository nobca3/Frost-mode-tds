-- WAVE 0
wait(2)
place(21.312, 3.879, 8.029, "Military Base", 400)

-- WAVE 1
wait(1)
upgrade(1, 1, 0)

-- WAVE 5
wait(2)
upgrade(1, 2, 0)

-- WAVE 10 (Placement du DJ comme dans la vidéo)
wait(2)
place(12.383, 3.899, 11.21, "DJ Booth", 1200)
wait(1)
upgrade(2, 1, 0)
ability(2, "TrackChange") -- Change de musique pour réduire les prix

-- WAVE 12
wait(2)
place(15.5, 3.899, 10.0, "Minigunner", 1850)
upgrade(3, 1, 0)

-- WAVE 15
wait(2)
place(-17.659, 3.899, 28.314, "Ranger", 4500)
upgrade(4, 1, 0)

-- WAVE 20 (Vente et Replacement)
wait(5)
sell(1) -- Supprime la Military Base
wait(1)
place(-1.083, 3.899, 12.946, "Turret", 5000)
upgrade(5, 1, 0)

-- FIN DE GAME ET CAPACITÉS
wait(10)
ability(2, "Ability") -- Boost du DJ
upgrade(5, 3, 0)

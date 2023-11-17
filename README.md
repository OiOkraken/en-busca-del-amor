# en-busca-del-amor
# Conectar funciones a teclas
window.listen()
window.onkeypress(up, 'Up')
window.onkeypress(down, 'Down')
window.onkeypress(left, 'Left')
window.onkeypress(right, 'Right')
# Bucle principal del juego
while True:
    window.update()  # Actualizar la pantalla
    border_collision()
    food_collision()
    bite()
    move_body()
    move()
    time.sleep(posponer)
la viborita

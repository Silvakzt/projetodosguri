# projetodosguri
Piano fodastico.
# parte 4 - alex
import pygame

def draw_menu(screen):
    font = pygame.font.SysFont("arial", 30)
    screen.fill((30, 30, 30))
    text = font.render("Bem-vindo ao Piano 🎹", True, (255, 255, 255))
    screen.blit(text, (200, 100))

    # Exemplo de botão
    pygame.draw.rect(screen, (100, 100, 255), (250, 180, 200, 50))
    button_text = font.render("Iniciar", True, (255, 255, 255))
    screen.blit(button_text, (300, 190))

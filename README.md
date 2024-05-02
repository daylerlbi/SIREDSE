import config
import data
import docente
import mockups

def main():
    print("Bienvenido al Sistema de Información y Red de Semilleros de Educación (SIREDSE)")
    print("Líder del Semillero:", config.lider_semillero['nombre'])
    print("Misión:", data.mision)
    print("Visión:", data.vision)
    print("Docente Ejemplo:", docente.Docente("Ana Martínez", "Profesora de Matemáticas").nombre)
    mockups.mostrar_mockup()

if __name__ == "__main__":
    main()

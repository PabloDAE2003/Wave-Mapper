Wave Mapper - Sistema de Procesamiento de Señales y Audio
Descripción General
Wave Mapper es una aplicación completa desarrollada en MATLAB App Designer para el procesamiento y manipulación de señales matemáticas y archivos de audio. La aplicación ofrece una interfaz intuitiva dividida en dos módulos especializados para procesamiento matemático y de audio.

Características Principales
Módulo de Señales Matemáticas
	Ingreso de funciones personalizadas (ej: sin(2pit), t.^2 + 3*t)
	Soporte para señales continuas y discretas
	Transformaciones temporales:
		Inversión (reflejo temporal)
		Escalamiento (compresión/expansión)
		Desplazamiento (corrimiento temporal)
		Operaciones combinadas
		Personalización de colores y parámetros
		Visualización en tiempo real
Módulo de Procesamiento de Audio
	Carga de múltiples formatos (MP3, WAV, M4A, FLAC, AAC)
	Reproducción integrada con controles (Play, Stop, Rewind)
	Efectos de audio:
		Inversión temporal (reproducción al revés)
		Compresión temporal (0.3x - 1.0x)
		Expansión temporal (1.0x - 3.0x)
	Visualización de formas de onda
	Sistema de reset y gestión de estado
Instalación y Ejecución
	Instalador Automático
	El instalador automático se encuentra en:
	Wave Mapper\Instalador\
	Pasos:
		Navegue a la carpeta Instalador
		Ejecute el archivo de instalación
		Siga las instrucciones del asistente
		La aplicación se instalará con todos los componentes necesarios
Archivo MLAPP
El archivo fuente de la aplicación se encuentra en:
Wave Mapper\MLAPP\Wave_Mapper.mlapp
Guía de Uso Rápida
	Procesamiento de Señales
	Seleccione el menú "Señales"
	Ingrese su función en el campo INGRESAR FUNCIÓN
	Configure parámetros de tiempo y tipo de señal
	Haga clic en "GRAFICAR" para visualizar
	Use los botones de transformación para aplicar efectos
Procesamiento de Audio
	Seleccione el menú "Audio"
	Haga clic en "Seleccionar Audio" para cargar un archivo
	Use los controles de reproducción para escuchar
	Aplique efectos con los botones correspondientes
	Use "Reset" para volver al estado inicial
Solución de Problemas
	Error al cargar archivos de audio
		Verifique que el formato sea compatible
		Confirme que el archivo no esté corrupto
	La aplicación no inicia
		Asegúrese de tener MATLAB R2019b o superior
		Verifique la instalación de los toolboxes requeridos
	Las transformaciones no funcionan
		Revise la sintaxis de las funciones matemáticas
		Confirme los rangos válidos para efectos de audio
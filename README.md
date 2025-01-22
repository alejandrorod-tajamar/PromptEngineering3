# Prompt Engineering 3

Para probar este proyecto, estos son los pasos a seguir:

1. Con una terminal de `Git Bash`, **clona** el repositorio:
   
   ```bash
   git clone https://github.com/alejandrorod-tajamar/PromptEngineering3.git
   ```
   
2. Abre una terminal de `Command Prompt`.
   
3. Navega al **directorio del proyecto**:
   
   ```cmd
   cd PromptEngineering3
   ```

4. Crea un **entorno virtual**:

   ```cmd
   python -m venv nombre_del_entorno
   ```

5. Activa el entorno virtual:

   ```cmd
   .\nombre_del_entorno\Scripts\activate
   ```

6. Instala en el entorno virtual el contenido del archivo `requirements.txt`:

   ```cmd
   pip install -r requirements.txt
   ```

7. Crea un archivo `.env` en el directorio raíz del proyecto con el siguiente contenido, reemplazando con tu Endpoint y tu clave de API:

   ```.env
   AZURE_OPENAI_API_KEY=tu_clave_api
   AZURE_OPENAI_ENDPOINT=tu_endpoint
   ```

8. Sigue las instrucciones en [07_prompt_engineering.ipynb](07_prompt_engineering.ipynb).

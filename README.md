# 📦 Streamlit ingesta de documentos y extraccion de metadatos
```
⬆️ Sreanlit, langchain, openai, pydantic, chroma

Esta aplicacion powered bny Papytum, esta pensada ara la ingesta de documentos y extraccion de documentos a una clase dinamica de Pydantic

## ingesta
Via llamaparser se realizara la ingesta del docuemnto pdf creando un mk.
Se spliteara y se crearan los embeddings via openai creando el vectorengine con chrome

## Creacion de Metadatos para su extraccion
Para esta funciona ademas se definiran via csv los metadatos y un texto para definir dicho metadato.

## ChatBot
Creacion del qa_chain con el prompt template, el vectorengine y su llm (REtrieval)

# Classificacao-de-marcas-de-carros-com-imagens

Este notebook foi adaptado para usar **o seu dataset no Google Drive** e executar o fluxo completo:

1. montar o Drive  
2. localizar as imagens em `archive_filtrado_15/image`  
3. contar classes e imagens  
4. separar em treino / validação / teste  
5. treinar um modelo **EfficientNet-B0**  
6. gerar curvas de treino  
7. gerar **matriz de confusão** e **matriz normalizada**  
8. salvar tudo de volta no Drive

> Estrutura esperada no Drive:
>
> `MyDrive/projeto_p/archive_filtrado_15/`
> - `image/`
> - `classes_escolhidas.txt` (opcional, mas recomendado)
> - `misc/`, `label/`, `part/`, `train_test_split/` (podem existir, mas o treino usa a pasta `image`)

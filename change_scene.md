Para cambiar el *Scene* cargaremos un nuevo *FXML* y lo asociaremos al *rootPane* ya existente (definido previamente en el *Scene Builder*):

    AnchorPane panel = FXMLLoader.load(getClass().getResource("/vista/nueva_ventana.fxml"));
    rootPane.getChildren().setAll(panel);
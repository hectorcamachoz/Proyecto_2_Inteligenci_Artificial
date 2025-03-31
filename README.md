# Proyecto_2_Inteligencia_Artificial

En este proyecto se utilizaran dos bases de datos proporcionadas por Kaggle especificamente de la competencia ["Spaceship Titanic"](https://www.kaggle.com/competitions/spaceship-titanic/overview). El objetivo de este proyecto es realizar algunos de los multiples modelos vistos en clase, como LDA, QDA, Regresion Logistica, Árboles de decisión, bagging, random forests, boosting, y seleccionar cual es el mejor, el resultado que se obtenga se mandara a la competencia de Kaggle. La variable de salida sera Transported que tiene como valores True o False.

Base de datos 1: train.csv

**PassengerId** - Un identificador único para cada pasajero. Cada Id tiene el formato gggg_pp, donde gggg indica un grupo con el que viaja el pasajero y pp es su número dentro del grupo. Las personas en un grupo suelen ser familiares, pero no siempre.

**HomePlanet** - El planeta del que partió el pasajero, típicamente su planeta de residencia permanente.

**CryoSleep** - Indica si el pasajero eligió ser puesto en animación suspendida durante el viaje. Los pasajeros en criosueño están confinados a sus cabinas.

**Cabin** - El número de la cabina donde se hospeda el pasajero. Tiene el formato cubierta/número/lado, donde el lado puede ser P para Puerto (izquierda) o S para Estribor (derecha).

**Destination** - El planeta al que el pasajero desembarcará.

**Age** - La edad del pasajero.

**VIP** - Indica si el pasajero pagó por un servicio VIP especial durante el viaje.

**RoomService**, **FoodCourt**, **ShoppingMall**, **Spa**, **VRDeck** - Cantidad que el pasajero ha gastado en cada una de las muchas instalaciones de lujo del Spaceship Titanic.

**Name** - El nombre y apellido del pasajero.

**Transported** - Indica si el pasajero fue transportado a otra dimensión. Esta es la variable objetivo, la columna que se intenta predecir.

Base de datos test.csv:

Cuenta con todas las variables exceptuando la variable Transported, ya que es la variable de salida.

Archivos que podras encontrar:
- [Reporte](P_P2_594557.html)
- [Reporte en ipynb](P_P2_594557.ipynb)
- [Archivo de resultados generado con modelo RF](results_(2).csv)
- [Archivo de resultados generado con modelo Boosting](results_boost_(1).csv)

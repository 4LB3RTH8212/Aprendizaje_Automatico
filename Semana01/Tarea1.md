# Semana 01: Preliminares
## Tarea 01: Selección de conjunto de datos 

### Definir el conjunto de datos.

Tras la revisin de diversos conjuntos de datos se opto por la opción de 2 dataset encontrados en kaggle [Credit Card Approval Prediction](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction). Tras una extensa busqueda por el origen de los datos no se encontro una respuesta exacta, el mismo autor menciona que no sabe el origen. Pero en sus discuciones pone un link como respuesta a la pregunta del [origen](https://mp.weixin.qq.com/s/upjzuPg5AMIDsGxlpqnoCg). Tambien como comentario menciono que los datos son bancarios reales sin informacion personal confidencial.

### Se cuentan con 2 tablas.

##### Registro_aplicación

| Nombre de la característica | Explicación | Observaciones |
|---------------------------|-------------|---------------|
| ID                        | Numero de cliente |               |
| CODE_GENDER               | Género |               |
| FLAG_OWN_CAR              | ¿Hay un coche? |               |
| FLAG_OWN_REALTY           | ¿Hay una propiedad? |               |
| CNT_CHILDREN              | Numero de niños |               |
| AMT_INCOME_TOTAL          | Ingresos anuales |               |
| NAME_INCOME_TYPE          | Categoría de ingresos |               |
| NAME_EDUCATION_TYPE       | Nivel de Educación |               |
| NAME_FAMILY_STATUS        | Estado civil |               |
| NAME_HOUSING_TYPE         | Modo de vivir |               |
| DAYS_BIRTH                | Cumpleaños | Cuente hacia atrás desde el día actual (0), -1 significa ayer |
| DAYS_EMPLOYED             | Fecha de inicio del empleo | Cuente hacia atrás desde el día actual (0). Si es positivo, significa la persona actualmente desempleada. |
| FLAG_MOBIL                | ¿Hay un teléfono móvil? |               |
| FLAG_WORK_PHONE           | ¿Hay un teléfono del trabajo? |               |
| FLAG_PHONE                | ¿Hay un teléfono? |               |
| FLAG_EMAIL                | ¿Hay un correo electrónico? |               |
| OCCUPATION_TYPE           | Ocupación |               |
| CNT_FAM_MEMBERS           | Tamaño de la familia |               |


##### Registro_crédito

| Nombre de la característica | Explicación | Observaciones |
|---------------------------|-------------|---------------|
| ID                        | Numero de cliente |               |
| MONTHS_BALANCE            | Mes récord | El mes de los datos extraídos es el punto de partida, hacia atrás, 0 es el mes actual, -1 es el mes anterior, y así sucesivamente. |
| STATUS                    | Estado | 0: 1-29 días de atraso 1: 30-59 días de atraso 2: 60-89 días de atraso 3: 90-119 días de atraso 4: 120-149 días de atraso 5: Deudas vencidas o incobrables, castigos por más de 150 días C: pagado ese mes X: No hay préstamo para el mes |

### Justificación de la Elección 
Me parece un tema interesante a tratar ya que puede darnos un filtro extra a la hora de la captacion de clientes si podemos lograr el predecir como se comportara el prospecto a cliente.

### Objetivos a Lograr.

Me gustaria encontrar llegar a una forma de etiquetar a un cliente como bueno o malo.

Verificar que caracteristicas del cliente influyen en su comportamiento.

Identificar patrones inusuales en los comportamientos 

Crear una evaluacion créditicia con la informacion del cliente y sus pagos.


# Cancer colorrectal
## Objetivo
Este dataset puede utilizarse para estudios de análisis de factores de riesgo, predicción de supervivencia, análisis de costos médicos y estudios epidemiológicos sobre el cáncer colorrectal.
## Descripcion
Este conjunto de datos contiene información sobre pacientes con cáncer colorrectal, incluyendo factores de riesgo, historial médico, tratamiento y predicciones de supervivencia.
## Estructura
El dataset se encuentra en la hoja colorectal_cancer_dataset y contiene las siguientes columnas:

Patient_ID: Identificador único del paciente.

Country: País de origen.

Age: Edad del paciente.

Gender: Género del paciente.

Cancer_Stage: Etapa del cáncer en el momento del diagnóstico.

Tumor_Size_mm: Tamaño del tumor en milímetros.

Family_History: Historial familiar de cáncer colorrectal.

Smoking_History: Historial de tabaquismo.

Alcohol_Consumption: Consumo de alcohol.

Obesity_BMI: Índice de masa corporal del paciente.

Diet_Risk: Riesgo dietético asociado al cáncer colorrectal.

Physical_Activity: Nivel de actividad física del paciente.

Diabetes: Presencia de diabetes.

Inflammatory_Bowel_Disease: Antecedentes de enfermedad inflamatoria intestinal.

Genetic_Mutation: Presencia de mutaciones genéticas relevantes.

Screening_History: Historial de exámenes de detección temprana.

Early_Detection: Indica si el cáncer fue detectado tempranamente.

Treatment_Type: Tipo de tratamiento recibido.

Survival_5_years: Probabilidad de supervivencia a 5 años.

Mortality: Indica si el paciente falleció debido al cáncer.

Healthcare_Costs: Costos médicos asociados al tratamiento.

Incidence_Rate_per_100K: Tasa de incidencia por cada 100,000 habitantes.

Mortality_Rate_per_100K: Tasa de mortalidad por cada 100,000 habitantes.

Urban_or_Rural: Indica si el paciente vive en una zona urbana o rural.

Economic_Classification: Nivel económico del paciente o país.

Healthcare_Access: Nivel de acceso a servicios de salud.

Insurance_Status: Estado del seguro médico del paciente.

Survival_Prediction: Predicción de supervivencia basada en múltiples factores.

## Alcance

Lo que se ha pretendido es mostrar los factores de riesgo más relevante en cuanto a la supervivencia del paciente.

## Desarrollo

Se ha comprobado la posible existencia de filas repetidas y nulos no existiendo ninguno de los dos.
Se ha traducido el texto de inglés a español
Se ha analizado en el libro seguro cada columna (factor) por separado teninendo en cuenta la característivas de los datos tanto cualitativos o categóricoa y cuantitativos, en otra hoja la relevancia de factor para la superviviencia de variables cualitativas y en otra algún factor más.

## Conclusion
Se ha comprobado que la dependencia de un sólo factor con respecto a la supervivencia no varía, estaría entorno al 60% de supervivencia y al 40% de no supervivencia. Sólo cuando se incluyen más factores podemos apreciar diferencia en cuanto a la supervivencia. Se han escogido mostrar los diferentes factores (segmentados) que dan lugar a variaciones importantes en la supervivencia en libro de dashboard.


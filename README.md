# iLADDER-OA

**In-silico LADDER: Lung Aerosol Dosimetry for Drug and Environmental Research**

<br>

This GitHub repository contains human oral airway geometries developed and used by the [in-silico LADDER](https://simtk.org/projects/insilico_ladder) team of investigators. You are welcome to download and use these geometries, but please cite the references associated with the downloaded models.

The repository includes the oral airway of 7 healthy male subjects and 4 male subjects with COPD. Details are as follows:

<br>

**Imaging**: multi-slice CT imaging of the head and torso (0.5 x 0.7 x 0.7 mm resolution, FOV 36 × 36 × 48 cm, i.e., image volume size of 512 × 512 × 960). 

**Segmentation**: based on intensity thresholding followed by visual validation and repair. 

**Model**: Mouth, oropharynx, larynx, vocal cord, and upper tracheal region. Mouthpiece and tubing are also included in the model.

**Mesh**: Hybrid prism/polyhedral volume meshes generated in ICEM-CFD 21.0 (~12 millions elements per model)

**Simulation types:** airflow and aerosol transport

**Simulation parameters:** flow rate: 18 and 45 L/min, tidal volume: 1 L, particle size: 1-30 µm

**Funding:** NIEHS U01 ES028669

**Related publications**: Borojeni et al., 2023 (https://doi.org/10.3390/pharmaceutics15010160) 

<br>

**This project is also available on** [**SimTK**](https://simtk.org/projects/insilico_ladder)**.**



### **Available Oral Airway Models**

| Subject ID | **Sex** | Age (Yrs) | Height (cm) | **BMI** | **Health Status** | **FEV1, %pred** | **FEV1/FVC** | **Mesh** | **Model**                                     |
| ---------- | ------- | --------- | ----------- | ------- | ----------------- | --------------- | ------------ | -------- | --------------------------------------------- |
| H1_PD01    | Male    | 35        | 170         | 23.5    | Healthy           | 113             | 0.88         | Yes      | [H1_PD01](INH/H1_PD01_UPPER_AIRWAY.stl)       |
| H2_PD02    | Male    | 52        | 165         | 35.5    | Healthy           | 117             | 0.79         | Yes      | [H2_PD02](INH/H2_PD02_UPPER_AIRWAY.stl)       |
| H3_PD03    | Male    | 47        | 183         | 26.5    | Healthy           | 85              | 0.74         | Yes      | [H3_PD03](INH/H3_PD03_UPPER_AIRWAY.stl)       |
| H4_PD07    | Male    | 26        | 183         | 27.5    | Healthy           | 94              | 0.80         | Yes      | [H4_PD07](INH/H4_PD07_UPPER_AIRWAY.stl)       |
| H5_PD08    | Male    | 34        | 193         | 26.8    | Healthy           | 104             | 0.84         | Yes      | [H5_PD08](INH/H5_PD08_UPPER_AIRWAY.stl)       |
| H6_PD20    | Male    | 21        | 168         | 19.2    | Healthy           | 89              | 0.73         | Yes      | [H6_PD20](INH/H6_PD20_UPPER_AIRWAY.stl)       |
| H7_PD21    | Male    | 21        | 173         | 21.3    | Healthy           | 95              | 0.81         | Yes      | [H7_PD21](INH/H7_PD21_UPPER_AIRWAY.stl)       |
| COPD1_PD09 | Male    | 57        | 164         | 26.1    | COPD              | 60              | 0.56         | Yes      | [COPD1_PD09](INH/COPD1_PD09_UPPER_AIRWAY.stl) |
| COPD2_PD10 | Male    | 55        | 178         | 20.8    | COPD              | 56              | 0.48         | Yes      | [COPD2_PD10](INH/COPD2_PD10_UPPER_AIRWAY.stl) |
| COPD3_PD13 | Male    | 45        | 180         | 25.6    | COPD              | 69              | 0.67         | Yes      | [COPD3_PD13](INH/COPD3_PD13_UPPER_AIRWAY.stl) |
| COPD4_PD19 | Male    | 54        | 187         | 24      | COPD              | 58              | 0.52         | Yes      | [COPD4_PD19](INH/COPD4_PD19_UPPER_AIRWAY.stl) |

 

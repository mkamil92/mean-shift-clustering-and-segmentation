# Mean Shift Clustering and Image Segmentation

This repository shows the application of the **Mean Shift algorithm** for clustering and segmentation tasks on two datasets:
1. **Bank Dataset**: Clustering customer data for segmentation.
2. **Image Dataset**: Segmenting an image into meaningful regions using the Mean Shift algorithm.

---

## Key Highlights

- **Bank Dataset**: 
  - Used Mean Shift clustering to identify customer segments based on demographic and transactional attributes.
  - Provided insights into customer behavior for targeted marketing and loyalty programs.

- **Image Dataset**:
  - Performed image segmentation using the Mean Shift algorithm.
  - Highlighted regions of interest in the image, showcasing the algorithm’s ability to group pixels into meaningful clusters based on their color intensity and spatial proximity.

---



## Workflow

### 1. Data Preprocessing
#### Bank Dataset:
- Scaled features using `StandardScaler` to normalize the data for clustering.
- Cleaned and handled missing values (if any).

#### Image Dataset:
- Converted the image into a feature matrix containing spatial and color information for each pixel.
- Rescaled the data for efficient clustering.

### 2. Mean Shift Algorithm
- Used the **Mean Shift algorithm** to perform clustering by identifying dense regions in the feature space.
- Tuned the bandwidth parameter to control the radius of the kernel used for density estimation.

### 3. Visualization
#### Bank Dataset:
- Visualized clusters in a 2D plane using **PCA** and **t-SNE** for dimensionality reduction.
- Highlighted customer segments with scatter plots.

#### Image Dataset:
- Segmented the image into distinct regions using the Mean Shift clustering results.
- Displayed the original image alongside the segmented version for comparison.

---

## Results

### Bank Dataset:
- Mean Shift successfully identified distinct customer segments.
- Clusters provided insights into customer behavior, enabling segmentation for targeted marketing campaigns.

### Image Dataset:
- Image segmentation produced clear and visually distinct regions, demonstrating the algorithm's ability to separate pixels based on both spatial proximity and color similarity.

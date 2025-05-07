# Marine-monitoring-YOLOv11
# Marine Pollution Detection with YOLOv11n and DCNv4


## Datasets

The datasets used in this study are publicly available:

1. **MADOS Dataset**:
   **Description**: The MADOS dataset is a high-resolution remote sensing dataset designed for marine pollution monitoring, covering various pollutant types such as oil spills, marine debris, foam, sea snot, and turbid water.
   **Access**: [MADOS Dataset](https://marine-pollution.github.io/)

2. **Trash-ICRA19 Dataset**:
   **Description**: The Trash-ICRA19 dataset is used for marine debris detection and includes images of surface debris, underwater trash, and artificial object remnants.
   **Access**: [Trash-ICRA19 Dataset](https://conservancy.umn.edu/items/c34b2945-4052-48fa-b7e7-ce0fba2fe649)

## Code

The code in this repository implements the improved YOLOv11n framework for marine pollution detection. The key features of the code include:
**Integration with DCNv4** to improve adaptability to deformable pollutants.
**Marine Fusion Loss (MFL)** for better handling of small-object detection and pollutant feature learning.
**Multi-scale Feature Fusion (MFF)** to improve the model’s robustness in complex marine environments.
**Experimental setup and model evaluation**, including mAP, precision, recall, and inference time metrics.

### Installation

To run the code, you'll need Python and some additional dependencies. Here’s how to set up the environment:

```bash
# Clone this repository
git clone https://github.com/your-username/marine-pollution-detection.git

# Change to the project directory
cd marine-pollution-detection

# Install the required dependencies
pip install -r requirements.txt

# PromptoLab-Data
Sample prompts as well as a prompt test set for the PromptoLab application

## Prerequisites

- Install the PromptoLab application, following the instructions in the following repo.
- [PromptoLab](https://github.com/crjaensch/PromptoLab)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/crjaensch/PromptoLab-Data
   ```

2. Copy both the `prompts` and `test_sets` directory to the parent directory of PromptoLab
   ```bash
   cd PromptoLab-Data
   mv prompts <parent-directory-of-PromptoLab-installation-dir>
   mv test_sets <parent-directory-of-PromptoLab-installation-dir>
   ```
## Running the Application

2. Run the application:
   ```bash
   # If inside PromptoLab, then move to the parent directory
   cd ..
   python3 -m PromptoLab

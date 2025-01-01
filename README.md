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

2. Copy the `prompts` and `test_sets` directory to the subdirectory ".promptolab" of the user's home directory
   ```bash
   cd PromptoLab-Data
   mv prompts $HOME/.promptolab/       # for Windows to: C:\Users\username\.promptolab
   mv test_sets $HOME/.promptolab/     # for Windows to: C:\Users\username\.promptolab
   ```
## Running the Application

2. Run the application:
   ```bash
   # If inside PromptoLab, then move to the parent directory
   cd ..
   python3 -m PromptoLab

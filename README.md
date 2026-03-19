# Service Registry - Distributed System Learning Project

### Cameron Ghaemmaghami (013120094)

### Prerequisites

Python 3.8 or higher

### Installation

1. **Create a virtual environment (Python 3.13+):**
```bash
cd ServiceRegistry
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

2. **Install dependencies:**
```bash
pip install -r requirements.txt
```

### Running the Service Registry
```bash
# Make sure virtual environment is activated
source venv/bin/activate

# Start the registry
python3 service_registry_improved.py
```

You should see:
```
Service Registry starting on port 5000...
Heartbeat timeout: 30s
Cleanup interval: 10s
```

The registry will start on `http://localhost:5001`


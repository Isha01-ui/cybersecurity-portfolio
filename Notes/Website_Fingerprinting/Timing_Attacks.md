## Concept
- Measures **response time differences** to infer information.  
- Safe practice: **use local test servers or lab environments only**.

## Key Steps
1. **Set up Python environment**  
   ```bash
   pip install requests


##Basic measurement##

import requests, time
start=time.time()
requests.get("http://localhost:5000/test")
end=time.time()
print(end-start)

##multiple measurements##

times=[]
for i in range(10):
    start=time.time()
    requests.get("http://localhost:5000/test")
    end=time.time()
    times.append(end-start)
print("Avg:", sum(times)/len(times))

Analyze patterns
	•	Longer/shorter times → potential info leak
	•	Optional: visualize with matplotlib

Real-World Conceptual Examples
	•	Website fingerprinting: identify visited sites via traffic patterns
	•	Crypto attacks: infer password or key info

Mitigation
	•	Random delays in responses
	•	Constant-time operations
	•	Avoid leaking timing info

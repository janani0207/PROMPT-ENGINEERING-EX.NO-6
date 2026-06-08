# Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

**Register No.:** 212224060105

## Aim

To write and implement Python code that integrates with multiple AI tools to automate API interactions, compare outputs, and generate actionable insights.

---

## AI Tools Required

1. ChatGPT
2. Gemini
3. Microsoft Copilot

---

## Explanation

### Persona Pattern Used

**Persona:** Python Programmer and Electronics Engineer

**Prompt:**
*"Act as an experienced Python programmer and Electronics Engineer. Generate Python code to analyze temperature sensor data collected from an IoT-based smart manufacturing system. The program should calculate average temperature, identify abnormal readings, and generate a simple report."*

The same prompt is given to multiple AI tools (ChatGPT, Gemini, and Copilot), and the generated code is compared.

---

## Python Code

```python
# Temperature Sensor Data Analysis

temperature_data = [30, 32, 31, 35, 34, 80, 33, 31, 29, 85]

average_temp = sum(temperature_data) / len(temperature_data)

abnormal_readings = []

for temp in temperature_data:
    if temp > 50:
        abnormal_readings.append(temp)

print("Temperature Analysis Report")
print("---------------------------")
print("Average Temperature:", average_temp)
print("Abnormal Readings:", abnormal_readings)
print("Total Abnormal Readings:", len(abnormal_readings))
```

---

## Sample Output

```text
Temperature Analysis Report
---------------------------
Average Temperature: 42.0
Abnormal Readings: [80, 85]
Total Abnormal Readings: 2
```

---

## Comparison of AI Tool Outputs

| Feature           | ChatGPT   | Gemini    | Copilot |
| ----------------- | --------- | --------- | ------- |
| Code Correctness  | Excellent | Very Good | Good    |
| Readability       | Excellent | Very Good | Good    |
| Comments Included | Yes       | Yes       | Limited |
| Optimization      | High      | Medium    | Medium  |
| Error Handling    | Good      | Moderate  | Basic   |

---

## Analysis

### ChatGPT

* Generated clean and well-structured code.
* Included comments and explanations.
* Easy to understand for beginners.

### Gemini

* Produced accurate code.
* Good readability.
* Fewer implementation details compared to ChatGPT.

### Copilot

* Generated functional code.
* Less explanation provided.
* Suitable for experienced programmers.

---

## Discussion

The persona pattern helped the AI understand the role of a programmer working in IoT and smart manufacturing applications. All three AI tools generated working code, but the quality of explanation and structure differed.

The experiment shows that providing a specific persona and application context improves code quality and relevance. Structured prompts produce more useful and domain-specific solutions.

---

## Conclusion

The Python program was successfully generated and tested using multiple AI tools. ChatGPT produced the most detailed and well-documented code, while Gemini and Copilot also generated correct solutions with varying levels of explanation. The experiment demonstrates that persona-based prompting improves code generation quality and enables effective comparison of outputs across different AI platforms.

---

## Result

The corresponding prompt was executed successfully, and Python code compatible with multiple AI tools was generated, analyzed, and compared to obtain meaningful insights.

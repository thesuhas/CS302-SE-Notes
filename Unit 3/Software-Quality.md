# Software Quality

- Quality can be visualised as Quality of the product vs Quality of the process used to build the product.
- Can involve checking whether the product/process conforms to certain norms - Verification and Validation.

#### FLURPS Model

- **F**unctionality or features
- **L**ocalisation to the local language
- **U**sability, intutivity, documentation, usually human factors.
- **R**eliability, frequency of failure and availability.
- **P**erformance such as speed, throughput and resource consumption.
- **S**upportability such as service and maintenance.

### Need for Measuring Quality

Quantifying quality is necessary in order to measure quality so that it can be enhanced.

- **Feedback**: Quantifies quality and helps in improving software quality.
- **Diagnostics**: Helps identify issues in software quality.
- **Forecasting**: Estimating, budgeting, costing and scheduling of future projects.

### Terminologies

- **Attribute**: measurable physical or abstract property of an entity.
- **Measure**: Quantitative indication of extent, amount, or size of some attribute. **Eg**: Number of errors
- **Metric**: Measure to degree of which a system, component or process possesses a given attribute. Calculation between two measures. **Eg**: Number of errors per person hours expended.

### Properties of Metric

- **Quantitative**: Metrics should be quantitative and expressed in values.
- **Understandable**: Should be easy to understand and be clearly defined.
- **Applicable**: Should be applicable in all phases of development.
- **Repeatable**: Should be same when measured repeatedly and needs to be consistent.
- **Economical**: computation should be economical.
- **Language Independent**: should not be dependent on programming languages.

### Cost of Software Quality (COSQ)

- Measure of quantifying and calculating the business value of quality activities.
- Considers the costs incurred in both meeting and not meeting customer's quality expectations.
- `Cost of Quality = Cost of Good Quality + Cost of Poor Quality`

### Categorisation of Metrics

- **Direct Measures**: Depends only on the value of the attribute. Other attributes are measured with respect to this. **Eg**: Cost, Effort, LoC, etc.
- **Indirect Measures**: Derived from direct measures. **Eg**: productivity
- **Size Oriented**: Size of the software produced. **Eg**: LoC, KLoC, Errors/KLoC, Defects/KLoC.
- **Complexity Oriented**: LoC, Fan-In Fan-Out
- **Product Metrics**: Assessing the state of project, tracking potential risks, evaluating teams ability to control quality.
- **Process Metrics**: Gaining insight of software engineering tasks. Used for long term process improvements.
- **Project Metrics**: Number of software developers, cost, schedule, staffing patterns.
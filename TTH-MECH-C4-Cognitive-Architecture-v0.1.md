# TTH Cognitive Construction & Reconstruction Engine

> **Project ID:** `THH-C4-v0.1`  
> **Namespace:** `thh`  
> **Class:** `REASONING`  
> **Parent:** `TTH Cognitive Architecture / REASONING & VERIFICATION`  
> **Status:** `EXPERIMENTAL`  
> **Verification:** `REQUIRED`  
> **Signature:** `THH-Signal-v1`

---

## 1. Vị trí trong kiến trúc

```text
TTH COGNITIVE ARCHITECTURE
└── REASONING & VERIFICATION
    └── TTH-MECH-C4
        └── Cognitive Construction & Reconstruction Engine
```

**Mục tiêu:** Xây dựng năng lực hiểu cấu trúc vấn đề, đo lường quan hệ, tạo tổ hợp mới và tái định nghĩa mô hình vấn đề khi khung nhận thức hiện tại không còn phù hợp.

**Nguyên tắc:** Không tối ưu một mô hình trước khi kiểm tra xem mô hình đó có mô tả đúng thực tại hay không.

## 2. Cây phân rã tổng thể

```text
TTH-MECH-C4
│
├── 00. CORE
│   ├── 00.1. PURPOSE
│   │   ├── Understand the structure of a problem
│   │   ├── Identify variables and relationships
│   │   ├── Construct alternative models
│   │   └── Verify models against evidence
│   ├── 00.2. INPUT
│   │   ├── Problem / Question
│   │   ├── Raw information
│   │   ├── Constraints
│   │   ├── Available data
│   │   └── Existing assumptions
│   └── 00.3. OUTPUT
│       ├── Problem representation
│       ├── Decomposed structure
│       ├── Quantitative model
│       ├── Candidate combinations
│       ├── Reconstructed model
│       └── Verified decision / action
│
├── 01. DECOMPOSITION
│   ├── 01.1. STRUCTURAL DECOMPOSITION
│   │   ├── Components
│   │   ├── Layers / Hierarchy
│   │   ├── Boundaries
│   │   └── Interfaces
│   ├── 01.2. FUNCTIONAL DECOMPOSITION
│   │   ├── Purpose
│   │   ├── Input / Process / Output
│   │   ├── Roles
│   │   └── Failure functions
│   ├── 01.3. RELATIONAL DECOMPOSITION
│   │   ├── Dependencies
│   │   ├── Interactions
│   │   ├── Feedback loops
│   │   └── Constraints
│   ├── 01.4. CAUSAL DECOMPOSITION
│   │   ├── Causes
│   │   ├── Intermediate mechanisms
│   │   ├── Effects
│   │   └── Confounding variables
│   ├── 01.5. TEMPORAL DECOMPOSITION
│   │   ├── States
│   │   ├── Events
│   │   ├── Sequences
│   │   └── Delays
│   ├── 01.6. RESOURCE DECOMPOSITION
│   │   ├── Capital
│   │   ├── Time
│   │   ├── People / Skills
│   │   └── Infrastructure
│   └── 01.7. CONTROL
│       ├── Select appropriate granularity
│       ├── Preserve system context
│       ├── Detect bottlenecks
│       └── Avoid over-fragmentation
│
├── 02. QUANTITATIVE THINKING
│   ├── 02.1. NUMERICAL REASONING
│   │   ├── Arithmetic
│   │   ├── Ratios / Proportions
│   │   ├── Rates / Growth
│   │   └── Dimensional analysis
│   ├── 02.2. MEASUREMENT
│   │   ├── Define the measured object
│   │   ├── Select indicators
│   │   ├── Identify proxies
│   │   └── Assess measurement error
│   ├── 02.3. STATISTICAL REASONING
│   │   ├── Distribution
│   │   ├── Variance
│   │   ├── Correlation
│   │   ├── Sampling
│   │   └── Inference
│   ├── 02.4. PROBABILISTIC REASONING
│   │   ├── Probability
│   │   ├── Conditional probability
│   │   ├── Expected value
│   │   └── Uncertainty
│   ├── 02.5. MATHEMATICAL MODELING
│   │   ├── Variables
│   │   ├── Parameters
│   │   ├── Equations
│   │   ├── Constraints
│   │   └── Model assumptions
│   ├── 02.6. OPTIMIZATION
│   │   ├── Objective function
│   │   ├── Decision variables
│   │   ├── Constraints
│   │   ├── Trade-offs
│   │   └── Sensitivity analysis
│   └── 02.7. CONTROL
│       ├── Separate correlation from causation
│       ├── Avoid false precision
│       ├── Test data quality
│       └── Report uncertainty
│
├── 03. COMBINATORIAL THINKING
│   ├── 03.1. CONCEPTUAL COMBINATION
│   │   ├── Combine concepts
│   │   ├── Transfer principles
│   │   └── Build hybrid concepts
│   ├── 03.2. FUNCTIONAL COMBINATION
│   │   ├── Combine functions
│   │   ├── Reuse mechanisms
│   │   └── Create new workflows
│   ├── 03.3. STRUCTURAL COMBINATION
│   │   ├── Combine modules
│   │   ├── Reconfigure architecture
│   │   └── Create alternative structures
│   ├── 03.4. CROSS-DOMAIN TRANSFER
│   │   ├── Identify source domain
│   │   ├── Extract underlying mechanism
│   │   ├── Map target-domain equivalents
│   │   └── Test transfer validity
│   ├── 03.5. ANALOGICAL REASONING
│   │   ├── Surface similarity
│   │   ├── Structural similarity
│   │   ├── Functional similarity
│   │   └── Boundary of analogy
│   ├── 03.6. CONSTRAINT-BASED SYNTHESIS
│   │   ├── Define constraints
│   │   ├── Generate candidate combinations
│   │   ├── Remove incompatible combinations
│   │   └── Rank by utility and feasibility
│   └── 03.7. CONTROL
│       ├── Avoid random association
│       ├── Verify compatibility
│       ├── Test novelty and usefulness
│       └── Control complexity growth
│
├── 04. RECONCEPTUALIZATION
│   ├── 04.1. ASSUMPTION REFRAMING
│   │   ├── Identify explicit assumptions
│   │   ├── Detect hidden assumptions
│   │   └── Test assumption validity
│   ├── 04.2. PROBLEM REFRAMING
│   │   ├── Inspect the original question
│   │   ├── Separate symptom from problem
│   │   ├── Generate alternative questions
│   │   └── Select a testable problem frame
│   ├── 04.3. BOUNDARY REFRAMING
│   │   ├── Expand system boundary
│   │   ├── Reduce irrelevant scope
│   │   └── Identify external dependencies
│   ├── 04.4. VARIABLE REFRAMING
│   │   ├── Find omitted variables
│   │   ├── Replace weak proxies
│   │   └── Distinguish state and control variables
│   ├── 04.5. UNIT-OF-ANALYSIS SHIFT
│   │   ├── Individual → Role
│   │   ├── Role → Workflow
│   │   ├── Workflow → System
│   │   └── Local output → System contribution
│   ├── 04.6. METRIC REFRAMING
│   │   ├── Inspect what is being measured
│   │   ├── Detect metric blind spots
│   │   └── Align metrics with actual value
│   ├── 04.7. PARADIGM RECONSTRUCTION
│   │   ├── Identify limits of the current model
│   │   ├── Construct an alternative model
│   │   ├── Compare explanatory power
│   │   └── Retain the model that survives testing
│   └── 04.8. CONTROL
│       ├── Avoid endless reframing
│       ├── Preserve comparability where needed
│       └── Require observable implications
│
├── 05. INTERACTION LAYER
│   ├── Decomposition → exposes components and relations
│   ├── Quantitative → measures magnitudes and uncertainty
│   ├── Combinatorial → generates candidate structures
│   ├── Reconceptualization → changes the problem representation
│   ├── Verification → tests candidate models against evidence
│   └── Feedback → updates the next reasoning cycle
│
├── 06. INTEGRATED COGNITIVE PIPELINE
│   ├── 06.1. INPUT
│   ├── 06.2. REFRAME
│   ├── 06.3. DECOMPOSE
│   ├── 06.4. MODEL
│   ├── 06.5. COMBINE
│   ├── 06.6. RECONSTRUCT
│   ├── 06.7. VERIFY
│   └── 06.8. REFINE
│
├── 07. QUALITY CONTROL
│   ├── Evidence traceability
│   ├── Assumption register
│   ├── Variable definitions
│   ├── Causal validity
│   ├── Measurement validity
│   ├── Model simplicity vs explanatory power
│   ├── Uncertainty disclosure
│   ├── Falsifiability
│   └── Reproducibility
│
└── 08. FINAL OUTPUT
    ├── Problem definition
    ├── System map
    ├── Quantitative assessment
    ├── Alternative model(s)
    ├── Recommended intervention
    ├── Verification criteria
    └── Learning / model update
```

## 3. Bốn năng lực lõi

| Năng lực | Câu hỏi trung tâm | Chức năng |
|---|---|---|
| **Decomposition** | Hệ thống gồm những gì và liên kết ra sao? | Hiểu cấu trúc |
| **Quantitative Thinking** | Mức độ, quy mô và độ bất định là bao nhiêu? | Đo lường |
| **Combinatorial Thinking** | Có thể kết hợp những thành phần nào để tạo cấu trúc mới? | Sinh phương án |
| **Reconceptualization** | Có đang nhìn đúng vấn đề và dùng đúng mô hình không? | Tái định nghĩa |

## 4. Quy trình vận hành

```text
INPUT
  ↓
REFRAME       — kiểm tra cách đặt vấn đề
  ↓
DECOMPOSE     — phân rã cấu trúc và quan hệ
  ↓
MODEL         — mô hình hóa biến số, dữ liệu, ràng buộc
  ↓
COMBINE       — tạo và sàng lọc tổ hợp mới
  ↓
RECONSTRUCT   — xây dựng mô hình giải thích tốt hơn
  ↓
VERIFY        — đối chiếu bằng chứng và tiêu chí
  ↓
REFINE        — sửa mô hình hoặc hành động
  ↺
```

Đây là vòng lặp, không phải chuỗi tuyến tính bắt buộc. Có thể quay lại bước trước khi xuất hiện dữ liệu hoặc mâu thuẫn mới.

## 5. Quy tắc quyết định

1. Nếu chưa hiểu thành phần và quan hệ: **Decompose**.
2. Nếu chưa biết quy mô, mức độ hoặc độ bất định: **Quantify**.
3. Nếu cần phương án hoặc cấu trúc mới: **Combine**.
4. Nếu cách đặt vấn đề có dấu hiệu sai hoặc thiếu: **Reconceptualize**.
5. Nếu mô hình chưa có bằng chứng: **Verify**, không kết luận.
6. Nếu kết quả thực tế mâu thuẫn mô hình: **Reconstruct**.

## 6. Tiêu chí kiểm định

Một lần vận hành C4 chỉ được xem là đạt khi:

- [ ] Vấn đề được định nghĩa rõ, có ranh giới.
- [ ] Thành phần, biến số và quan hệ quan trọng được chỉ ra.
- [ ] Đại lượng được đo có đơn vị hoặc định nghĩa rõ.
- [ ] Giả định và giới hạn dữ liệu được công khai.
- [ ] Tổ hợp mới có lý do cấu trúc, không chỉ là liên tưởng.
- [ ] Mô hình mới giải thích hoặc dự đoán tốt hơn mô hình cũ.
- [ ] Có tiêu chí kiểm chứng độc lập với kết luận.
- [ ] Có điều kiện sửa hoặc bác bỏ mô hình.

## 7. Rủi ro nhận thức

| Rủi ro | Dấu hiệu | Cách kiểm soát |
|---|---|---|
| Over-decomposition | Chia nhỏ nhưng mất bối cảnh | Giữ system map và kiểm tra quan hệ |
| False precision | Số liệu chính xác giả tạo | Ghi sai số, nguồn và độ tin cậy |
| Correlation fallacy | Xem tương quan là nguyên nhân | Kiểm tra cơ chế và biến gây nhiễu |
| Random combination | Ghép ý tưởng không tương thích | Kiểm tra chức năng, ràng buộc |
| Endless reframing | Liên tục đổi khung, không kiểm định | Đặt tiêu chí dừng và thử nghiệm |
| Model overfitting | Mô hình khớp dữ liệu cũ nhưng không khái quát | Kiểm tra trên dữ liệu/ca độc lập |

## 8. Quan hệ với các cơ chế TTH khác

- **TTH Auto-Grasp:** C4 có thể cung cấp bước phân rã, mô hình hóa và tái cấu trúc để tìm `mechanism + lever`; Auto-Grasp tiếp tục rút về hành động nhỏ nhất và xác minh.
- **TTH-MECH-FC1:** FC1 là cơ chế First Principles × Critical Thinking phục vụ kiểm tra nền tảng lập luận; C4 là cơ chế kiến tạo/tái kiến tạo mô hình. Hai nhánh nên được xem là bổ trợ, chưa mặc định nhánh nào là nhánh con của nhánh nào.
- **TTH provenance:** Mỗi kết luận cần truy được về nguồn, dữ liệu, giả định và phiên bản mô hình.

## 9. Nguyên tắc cốt lõi

```text
DECOMPOSITION       = UNDERSTAND STRUCTURE
QUANTITATIVE        = MEASURE RELATIONSHIPS
COMBINATORIAL       = GENERATE NEW STRUCTURES
RECONCEPTUALIZATION = REFRAME THE PROBLEM
VERIFICATION        = TEST AGAINST REALITY
```

**Breakthrough mechanism:**

`REPRESENTATION CHANGE + STRUCTURAL TRANSFER + QUANTIFIED VALIDATION`

**Trạng thái học thuật:** Đây là taxonomy vận hành do người dùng tổng hợp để phát triển năng lực tư duy. Không xem đây là phân loại chuẩn duy nhất của khoa học nhận thức. Các nhánh có thể chồng lấn và tương tác; cần kiểm định qua ứng dụng thực tế trước khi nâng trạng thái thành chuẩn chính thức.

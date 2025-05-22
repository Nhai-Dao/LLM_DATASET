# edabk-ic-design-dataset

A benchmark dataset for digital circuit design (Digital IC Design)

## 1. Overview of the Benchmark

<table style="width:100%; border-collapse: collapse; margin: 25px 0; font-size: 0.9em; font-family: sans-serif; box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);">
    <thead>
        <tr style="background-color: #009879; color: #ffffff; text-align: left;">
            <th style="padding: 12px 15px;">Level</th>
            <th style="padding: 12px 15px;">Description</th>
            <th style="padding: 12px 15px;">Topics</th>
        </tr>
    </thead>
    <tbody>
        <tr style="border-bottom: 1px solid #dddddd;">
            <td style="padding: 12px 15px; background-color: #f3f3f3;"><strong>Level 1: Basic Theory</strong></td>
            <td style="padding: 12px 15px;">Foundational knowledge and concepts</td>
            <td style="padding: 12px 15px;">
                <ul style="margin: 0; padding-left: 20px;">
                    <li>Definitions and fundamental concepts</li>
                    <li>Steps to design a digital circuit</li>
                    <li>Circuit optimization process</li>
                    <li>Circuit verification methods</li>
                </ul>
            </td>
        </tr>
        <tr style="border-bottom: 1px solid #dddddd;">
            <td style="padding: 12px 15px; background-color: #f3f3f3;"><strong>Level 2: Basic Calculations</strong></td>
            <td style="padding: 12px 15px;">Essential numerical operations</td>
            <td style="padding: 12px 15px;">
                <ul style="margin: 0; padding-left: 20px;">
                    <li>Binary to decimal conversion</li>
                    <li>Binary arithmetic</li>
                    <li>Basic logic calculations</li>
                </ul>
            </td>
        </tr>
        <tr style="border-bottom: 1px solid #dddddd;">
            <td style="padding: 12px 15px; background-color: #f3f3f3;"><strong>Level 3: Minimization and Proof</strong></td>
            <td style="padding: 12px 15px;">Advanced logic operations</td>
            <td style="padding: 12px 15px;">
                <ul style="margin: 0; padding-left: 20px;">
                    <li>Logic function minimization</li>
                    <li>Formula proof</li>
                    <li>Applying theory to practical problems</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td style="padding: 12px 15px; background-color: #f3f3f3;"><strong>Level 4: Circuit Implementation</strong></td>
            <td style="padding: 12px 15px;">Practical circuit design</td>
            <td style="padding: 12px 15px;">
                <ul style="margin: 0; padding-left: 20px;">
                    <li>Converting formulas to circuits</li>
                    <li>Designing circuits from specifications</li>
                    <li>Circuit structure optimization</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

## 2. Dataset Scale

### Số lượng và phân loại dữ liệu

Dataset được chia thành 3 nhóm chính tương ứng với 3 level đầu tiên:

<table style="width:100%; border-collapse: collapse; margin: 25px 0; font-size: 0.9em; font-family: sans-serif; box-shadow: 0 0 20px rgba(0, 0, 0, 0.15);">
    <thead>
        <tr style="background-color: #009879; color: #ffffff; text-align: left;">
            <th style="padding: 12px 15px;">Level</th>
            <th style="padding: 12px 15px;">Tên</th>
            <th style="padding: 12px 15px;">Số lượng</th>
            <th style="padding: 12px 15px;">Mô tả</th>
        </tr>
    </thead>
    <tbody>
        <tr style="border-bottom: 1px solid #dddddd;">
            <td style="padding: 12px 15px; background-color: #f3f3f3;">1</td>
            <td style="padding: 12px 15px;">Lý thuyết cơ bản</td>
            <td style="padding: 12px 15px;">436</td>
            <td style="padding: 12px 15px;">Các câu hỏi lý thuyết tổng hợp, bao phủ toàn bộ các chủ đề trọng tâm của điện tử số</td>
        </tr>
        <tr style="border-bottom: 1px solid #dddddd;">
            <td style="padding: 12px 15px; background-color: #f3f3f3;">2</td>
            <td style="padding: 12px 15px;">Tính toán cơ bản</td>
            <td style="padding: 12px 15px;">4090</td>
            <td style="padding: 12px 15px;">Chủ yếu là các bài toán chuyển đổi hệ số, phép toán nhị phân, số bù, số dấu, ...</td>
        </tr>
        <tr>
            <td style="padding: 12px 15px; background-color: #f3f3f3;">3</td>
            <td style="padding: 12px 15px;">Tối thiểu hóa hàm/Karnaugh Map</td>
            <td style="padding: 12px 15px;">7200</td>
            <td style="padding: 12px 15px;">Các bài toán tối thiểu hóa hàm logic với K-map 3, 4, 5, 6 biến</td>
        </tr>
    </tbody>
</table>

### Thống kê chi tiết

#### Level 1: Lý thuyết cơ bản
<div style="background-color: #f8f9fa; padding: 20px; border-radius: 8px; margin: 15px 0;">
    <h4 style="color: #009879; margin-top: 0;">Tổng quan</h4>
    <ul style="list-style-type: none; padding-left: 0;">
        <li style="margin: 10px 0;">📚 <strong>436</strong> câu hỏi lý thuyết</li>
        <li style="margin: 10px 0;">✓ Được crawl và kiểm tra thủ công</li>
    </ul>
</div>

#### Level 2: Tính toán cơ bản
<div style="background-color: #f8f9fa; padding: 20px; border-radius: 8px; margin: 15px 0;">
    <h4 style="color: #009879; margin-top: 0;">Phân bố bài tập (4090 bài)</h4>
    <table style="width:100%; border-collapse: collapse; margin: 15px 0;">
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px; width: 60%;">Chuyển đổi hệ số</td>
            <td style="padding: 8px; text-align: right;"><strong>3072</strong> bài (75%)</td>
        </tr>
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px;">Bài toán nhị phân</td>
            <td style="padding: 8px; text-align: right;"><strong>100</strong> bài (2%)</td>
        </tr>
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px;">Số dấu</td>
            <td style="padding: 8px; text-align: right;"><strong>312</strong> bài (8%)</td>
        </tr>
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px;">Số bù 1</td>
            <td style="padding: 8px; text-align: right;"><strong>297</strong> bài (7%)</td>
        </tr>
        <tr>
            <td style="padding: 8px;">Số bù 2</td>
            <td style="padding: 8px; text-align: right;"><strong>309</strong> bài (8%)</td>
        </tr>
    </table>
</div>

#### Level 3: K-map
<div style="background-color: #f8f9fa; padding: 20px; border-radius: 8px; margin: 15px 0;">
    <h4 style="color: #009879; margin-top: 0;">Phân bố K-map (7200 bài)</h4>
    <table style="width:100%; border-collapse: collapse; margin: 15px 0;">
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px; width: 60%;">K-map 3 biến</td>
            <td style="padding: 8px; text-align: right;"><strong>3500</strong> bài (49%)</td>
        </tr>
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px;">K-map 4 biến</td>
            <td style="padding: 8px; text-align: right;"><strong>3500</strong> bài (49%)</td>
        </tr>
        <tr style="border-bottom: 1px solid #ddd;">
            <td style="padding: 8px;">K-map 5 biến</td>
            <td style="padding: 8px; text-align: right;"><strong>100</strong> bài (1%)</td>
        </tr>
        <tr>
            <td style="padding: 8px;">K-map 6 biến</td>
            <td style="padding: 8px; text-align: right;"><strong>100</strong> bài (1%)</td>
        </tr>
    </table>
</div>

### Dataset visualization

![*Total data by group*](https://github.com/duonggiang156/banchmark-edabk/blob/master/images/total.jpg)

![*Distribution of problem types in Level 2*](https://github.com/duonggiang156/banchmark-edabk/blob/master/images/level2-data.jpg)

![*Distribution of problem types in Level 3*](https://github.com/duonggiang156/banchmark-edabk/blob/master/images/level3-data.jpg)


## 3. Usage Guide

### Environment
- Python >= 3.x
- Required libraries: `pandas`, `numpy`, `...`

### Benchmark usage workflow

```
Step 1: Clone repository
    |
Step 2: Install dependencies
    |
Step 3: Run benchmark with the corresponding dataset
    |
Step 4: Evaluate results using metrics
```

### Detailed steps

1. **Clone repository**
   ```bash
   git clone <link-repo>
   cd <repo-folder-name>
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run benchmark**
   - Follow the instructions in the `src/` directory or use the provided notebook/scripts.

4. **Evaluate results**
   - Use the following metrics:
     - Accuracy
     - Processing time
     - Solution complexity

## 🎯 Benchmark Goals

- Provide a standardized, easy-to-use dataset for digital circuit design problems.
- Support evaluation and comparison of AI/LLM models in digital electronics.
- Enable expansion, contribution, and reuse of data within the research community.

## 🚀 Quick Start

1. Clone repository:
   ```bash
   git clone <link-repo>
   cd <repo-folder-name>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run a sample script:
   ```bash
   python src/run_benchmark.py --dataset 1cau_convert_so.xlsx
   ```

## 🤝 Contribution & Development

- All contributions regarding data, code, or ideas are welcome!
- Please create a pull request or issue for discussion.
- To develop more benchmarks or expand the dataset, refer to the `src/` directory and contact the development team.

## 📄 Citation

If you use this dataset for research, please cite as follows:

```
@misc{edabk-ic-design-dataset,
  title={edabk-ic-design-dataset: Benchmark for digital circuit design},
  author={Nhai-Dao},
  year={2024},
  url={https://github.com/Nhai-Dao}
}
```






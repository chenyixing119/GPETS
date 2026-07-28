# Gravitational Penetration Evidence Chain: A Century of Experimental Constraints (with Open Questions)

**Author**: Chen Yixing  
**Date**: July 23, 2026  
**Contact**: chenyixing.acad@foxmail.com  

---

## Abstract

When a gravitational field encounters macroscopic matter, is it absorbed, reflected, or fully penetrating? This paper systematically reviews experimental evidence from the past century, establishing a complete evidence chain: (1) laboratory torsion balances and lunar occultation analyses have excluded gravitational absorption to extremely high precision; (2) lunar laser ranging constrains any residual absorption coefficient to the $10^{-22}\,\text{m}^2/\text{kg}$ level, equivalent to complete penetration; (3) precision tests of the equivalence principle (MICROSCOPE, Eöt-Wash, LLR) demonstrate that gravity penetrates matter without composition-dependent variation; (4) wide binary stars in the low-acceleration regime show indications of gravitational enhancement (Chae 2023 reports 8.7σ), but this signal remains controversial. This paper aims to provide a solid experimental foundation for future theoretical work, without presupposing any unverified theoretical framework.

---

## 1. Introduction

Gravity is the only fundamental interaction that manifests as attraction at all scales, yet what happens when a gravitational field encounters matter is rarely systematically questioned. If gravity were absorbed like light, a "gravitational shadow" should appear behind the Earth; if reflected, the equivalence principle would be violated. These questions can be answered directly by experiment.

This paper organizes evidence into three tiers:
- **Tier 1**: Gravity is not absorbed or reflected by matter (strong experimental constraint)
- **Tier 2**: Gravity fully penetrates matter without composition-dependent variation within the Solar System (strong experimental constraint)
- **Tier 3**: In low-acceleration/low-density regimes, penetration may be accompanied by modulation of the effective gravitational coupling (open question, pending test)

---

## 2. Tier 1: Gravity Is Not Absorbed or Reflected

### 2.1 Theoretical Expectations and Experimental Tests

Two distinct classes of gravitational shielding models have appeared in history. Le Sage (1784) proposed a corpuscular impact model, in which gravity arises from isotropic particle flux pushing objects, with matter obstruction producing a "gravitational shadow." Majorana (1919) proposed a different attenuation model, assuming gravitational flux decays exponentially through matter, quantified by an absorption coefficient $h$. These models differ mechanistically but share the common prediction that gravity can be attenuated by matter, allowing a unified constraint via $h$.

### 2.2 Laboratory Torsion Balance Experiments

Majorana himself measured $h \leq 4.3 \times 10^{-14}\,\text{cm}^2/\text{g}$ (equivalent to $4.3 \times 10^{-15}\,\text{m}^2/\text{kg}$) using lead balls and a torsion balance. Subsequent improvements (Kreuzer 1966, Panov 1985) maintained the limit at $h \leq 10^{-15}\,\text{m}^2/\text{kg}$, confirming and slightly tightening Majorana's result. Savrov (2012) systematically confirmed the validity of these data and unified the definition standards across different references.

### 2.3 Lunar Occultation Gravity Anomaly Analysis

During lunar eclipses, if the Moon shields solar gravity, ground gravimeters should register anomalies. Multiple analyses in the 1970s–1990s (Saxl & Allen 1971, Van Flandern 1975) found no such anomalies, pushing the $h$ upper limit down to $6 \times 10^{-19}\,\text{m}^2/\text{kg}$. It should be noted that Saxl & Allen's experiment used pendulum clocks and later studies suggested possible environmental influences (temperature, air pressure). Nevertheless, subsequent more precise observations (especially LLR) have ruled out shielding with far higher confidence, so the overall evidence chain remains robust.

### 2.4 Lunar Laser Ranging (LLR): The Strongest Constraint

Fifty years of continuous LLR data track the Moon's orbit to test whether the Earth and Moon fall toward the Sun with equal acceleration. If gravitational shielding existed, the Earth's "shadow" would cause a slight difference in the solar gravitational force experienced by the Moon. Williams, Turyshev & Boggs (2009) obtained:

$$h = (3 \pm 5) \times 10^{-22}\,\text{m}^2/\text{kg}$$

This is the strongest constraint to date, 7 orders of magnitude tighter than laboratory results and 3 orders tighter than occultation analyses.

**Conclusion**: Gravitational shielding (absorption/reflection) is excluded to extremely high precision. Gravity must fully penetrate matter, producing no observable "shadow" or "rebound."

---

## 3. Tier 2: Complete Penetration Without Composition Dependence

### 3.1 Weak Equivalence Principle: MICROSCOPE

The French MICROSCOPE satellite (2016–2018) placed titanium and platinum test masses in a 710 km orbit, measuring their differential free-fall acceleration. Touboul et al. (2022) reported:

$$\eta = (a_{\text{Ti}} - a_{\text{Pt}}) / (a_{\text{Ti}} + a_{\text{Pt}}) \leq 2.7 \times 10^{-15}$$

Gravity acts identically on different compositions to better than 1 part in $10^{15}$.

### 3.2 Eöt-Wash Torsion Balance

The Eöt-Wash series (Schlamminger et al. 2008) used a rotating torsion balance to compare accelerations of beryllium and titanium, giving $\eta \leq 10^{-13}$ across multiple material combinations.

### 3.3 Strong Equivalence Principle: LLR

The SEP requires that gravitational self-energy also participates normally in free fall. The Earth's gravitational self-energy is about $4.6 \times 10^{-10}$ of its mass. LLR constrains any differential acceleration to:

$$(M_G / M_I - 1) = (2 \pm 5) \times 10^{-13}$$

(Williams, Turyshev & Boggs 2009).

**Conclusion**: At Solar System scales, gravity fully penetrates matter and acts identically on all compositions and forms of energy. The equivalence principle holds to $10^{-15}$.

---

## 4. Tier 3: Indications of Modulation in the Low-Acceleration Regime (Open Question)

### 4.1 Wide Binary Anomaly

Wide binaries are stellar pairs separated by thousands of AU, orbiting with accelerations below $10^{-9}\,\text{m/s}^2$—ideal laboratories for testing gravity in the low-acceleration regime. Chae (2023, ApJ 952, 128) analyzed 26,615 wide binaries from Gaia DR3 and found:

$$\gamma \equiv G_{\text{eff}} / G_N = 1.43 \pm 0.06$$

Deviation from Newtonian gravity: **8.7σ**. This result is qualitatively consistent with predictions of Modified Newtonian Dynamics (MOND), which posits enhanced gravitational strength below a critical acceleration threshold.

### 4.2 Controversy and Technical Background

Banik et al. (2024, MNRAS 527, 1148) obtained results consistent with Newtonian gravity ($\gamma = 1.12^{+0.27}_{-0.22}$, 0.4σ) using different sample selection and orbit modeling. Key controversial points include:
- Sample selection: whether unresolved triple systems are included;
- Orbit modeling: appropriateness of prior distributions;
- Stellar mass estimation accuracy.

Additionally, Gaia DR3 astrometric data exhibit significant excess noise, possibly from unresolved companions or instrumental systematics. The effect of this noise on wide binary orbit fitting remains under investigation and is a key technical background to the controversy.

Hernandez & Kroupa (2024, arXiv:2410.17178) noted that analyses favoring Newtonian gravity have issues in sample selection and statistical methodology, while the anomaly-supporting team used more conservative samples.

### 4.3 Current Status

The wide binary anomaly is **not settled** but remains a significant observational indication. It may arise from systematics, unknown tertiary contamination, or genuine new physics. If the latter, it would suggest that in extremely low-density/low-acceleration environments, gravitational penetration may be accompanied by modulation of the effective coupling strength.

**Conclusion**: Tier 3 evidence remains open, awaiting independent data. Gaia DR4 (expected late 2026 to early 2027) will provide ~10⁶ astrometric orbit solutions, potentially resolving the signal at decisive significance.

---

## 5. Evidence Chain Summary

| Tier | Proposition | Status | Key Experiment |
|---|---|---|---|
| 1 | No absorption/reflection | Strong constraint | LLR: $h = (3\pm5)\times10^{-22}\,\text{m}^2/\text{kg}$ |
| 2 | Penetration without composition dependence | Strong constraint | MICROSCOPE: $\eta \leq 2.7\times10^{-15}$ |
| 3 | Possible modulation in low-acceleration regime | Controversial | Wide binaries: $\gamma \approx 1.43$, 8.7σ (under debate) |

---

## 6. Conclusions

Based on a systematic review of experimental evidence over the past century, we conclude:

1. **Gravity is not absorbed or reflected by matter** – LLR constrains any residual absorption to $10^{-22}\,\text{m}^2/\text{kg}$, excluding absorption/reflection models with extremely high precision.
2. **Gravity fully penetrates matter without composition-dependent variation** – the equivalence principle holds to $10^{-15}$.
3. **In low-acceleration/low-density regimes, gravitational modulation remains an open question** – the wide binary signal (8.7σ) indicates an ~40% enhancement of the effective gravitational constant, but the signal is controversial and awaits Gaia DR4 for resolution.

These three tiers form a complete logical chain: from the established fact that gravity penetrates matter, to the open question of whether penetration may involve modulation. They provide a solid experimental foundation for future theoretical research and observational tests.

> **Note**: "Penetration" here is used phenomenologically—gravity shows no detectable attenuation from macroscopic matter. In General Relativity, gravity is spacetime curvature, not particle flux through matter.

---

## References

1. Chae, K.-H. 2023, *ApJ*, 952, 128.
2. Touboul, P. et al. 2022, *Phys. Rev. Lett.*, 129, 121102.
3. Williams, J.G., Turyshev, S.G., Boggs, D.H. 2009, *Int. J. Mod. Phys. D*, 18, 1129.
4. Schlamminger, S. et al. 2008, *Phys. Rev. Lett.*, 101, 041102.
5. Banik, I. et al. 2024, *MNRAS*, 527, 1148.
6. Hernandez, X. & Kroupa, P. 2024, arXiv:2410.17178.
7. Savrov, L.A. 2012, *Grav. Cosmol.*, 18, 271.

---

**Author Statement**: This is an experimental evidence review, presupposing no unverified theoretical framework. All conclusions are based on published experimental data. Verification, discussion, and criticism are welcome.

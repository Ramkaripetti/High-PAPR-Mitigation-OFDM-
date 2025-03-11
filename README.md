# High-PAPR-Mitigation-OFDM-

Orthogonal Frequency Division Multiplexing (OFDM) has emerged as a cornerstone technology for modern wireless communication systems, including 4G, 5G, and beyond. Its inherent advantages, such as high spectral efficiency, robustness to multipath fading, and ease of implementation, make it a preferred choice for many applications. However, the widespread adoption of OFDM is hindered by certain challenges, with the Peak-to-Average Power Ratio (PAPR) being one of the most critical issues.

A high PAPR results in significant power inefficiency in non-linear components, such as power amplifiers, leading to signal distortion and reduced system performance. To address this, several PAPR reduction techniques have been developed, including clipping and filtering, Partial transmit sequence (PTS), $\mu$ -law companding, and advanced approaches like Airy-based companding.

This study focuses on analyzing the impact of PAPR on OFDM signals, comparing various reduction techniques, and evaluating their performance under different fading channels with 8-PSK and 16-QAM modulation schemes. By leveraging MATLAB simulations, we assess the Complementary Cumulative Distribution Function (CCDF) of PAPR, highlighting the suitability of each technique for real-world wireless communication systems.

This work aims to contribute to the understanding and optimization of PAPR reduction methods, paving the way for more efficient and reliable OFDM-based communication systems.

In this work, various high PAPR reduction techniques were evaluated under different fading channel conditions, specifically Rayleigh, Rician, and Nakagami channels. The primary objective was to assess the effectiveness of these techniques in mitigating the effects of high PAPR in OFDM systems.

Key findings from the study include:

### Fig1: Under Rayleigh Channel Fading , CCDF vs PAPR_thresholds
![Rayleigh](https://github.com/user-attachments/assets/3682b91d-d59c-496a-b0bd-231ac0c20b1c)
### Fig2: Under Rician Channel Fading , CCDF vs PAPR_thresholds
![Rician](https://github.com/user-attachments/assets/56271657-0f12-4a45-bcd0-a69a1d4c0014)
### Fig3: Under Nakagami Channel Fading , CCDF vs PAPR_thresholds
![Nakagami](https://github.com/user-attachments/assets/853d737b-c2c9-4a6c-87df-3f552fefae94)


## Conclusion

1.8-PSK performed better than 16-QAM}: The results showed that 8-PSK modulation provided better PAPR reduction compared to 16-QAM under all fading conditions. This is primarily because 8-PSK has a lower constellation size, which reduces the amplitude variations, leading to lower PAPR.

2.The Nakagami fading channel, especially with moderate values of the Nakagami parameter \(m > 1\), provided the most favorable environment for PAPR reduction techniques. It balanced signal stability and fading, allowing techniques like clipping, PTS, and companding to perform effectively with minimal distortion.

3.Among the evaluated techniques, Clipping followed by Airy Companding performed the best overall in terms of reducing PAPR. Clipping was particularly effective, but it is not suitable for very high PAPR values due to the introduced distortion. Airy Companding showed promising results in maintaining signal quality while reducing peaks, making it a viable option in high PAPR environments.

In conclusion, this work highlights the importance of selecting the appropriate modulation scheme, fading channel model, and PAPR reduction technique for improving the efficiency of communication systems. The Nakagami fading channel with moderate fading conditions and 8-PSK modulation provide the most reliable performance, while Clipping and Airy Companding offer effective PAPR reduction strategies, with careful consideration needed for high PAPR scenarios.



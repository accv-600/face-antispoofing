# Semi-Supervised Learning for Face Anti-Spoofing Using Apex Frame

Face Anti-Spoofing (FAS) is designed to identify fraudulent attempts aimed at bypassing a facial recognition system using photos, videos, masks, or other counterfeit faces. One of the major challenges faced by FAS is the domain shift problem, which arises from differences in data distributions between training and testing sets. To alleviate this issue, this work introduces a generalized FAS method within the semi-supervised learning (SSL) paradigm. Specifically, we first present the concept of an apex frame, which summarizes the entire video in a single frame. This is achieved by computing a weighted sum of all frames, where the weights are assigned based on a Gaussian distribution centered around the video’s center frame. Next, we generate multiple unlabeled apex frames by exploring various temporal lengths, which serve as pseudo-labels to facilitate semi-supervised learning. Finally, a novel Gaussian-weighted loss function is introduced that adjusts the pseudo-loss based on the confidence scores that have been smoothed with a Gaussian kernel. Our experimental results from four face anti-spoofing databases (CASIA, Replay-attack, OULU-NPU, and MSU-MFSD) demonstrate that the proposed apex frames, combined with the semi-supervised mechanism and a Gaussian-guided pseudo-loss, enable more robust detection.

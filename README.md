# Leblois A, Boraud T, Meissner W, Bergman H, Hansel D (2006)
Competition between Feedback Loops Underlies Pathological Dynamics in the Basal Ganglia
*J Neurosci* 26(13):3567-3583

## Abstract

Experiments performed in normal animals suggest that the basal ganglia (BG) are crucial in motor program selection. BG are also involved in movement disorders. In particular, BG neuronal activity in parkinsonian animals and patients is more oscillatory and more synchronous than in normal individuals. We propose a new model for the function and dysfunction of the motor part of BG. We hypothesize that the striatum, the subthalamic nucleus, the internal pallidum (GPi), the thalamus, and the cortex are involved in closed feedback loops. The direct (cortex-striatum-GPi-thalamus-cortex) and the hyperdirect loops (cortex-subthalamic nucleus-GPi-thalamus-cortex), which have different polarities, play a key role in the model. We show that the competition between these two loops provides the BG-cortex system with the ability to perform motor program selection. Under the assumption that dopamine potentiates corticostriatal synaptic transmission, we demonstrate that, in our model, moderate dopamine depletion leads to a complete loss of action selection ability. High depletion can lead to synchronous oscillations. These modifications of the network dynamical state stem from an imbalance between the feedback in the direct and hyperdirect loops when dopamine is depleted. Our model predicts that the loss of selection ability occurs before the appearance of oscillations, suggesting that Parkinson's disease motor impairments are not directly related to abnormal oscillatory activity. Another major prediction of our model is that synchronous oscillations driven by the hyperdirect loop appear in BG after inactivation of the striatum.

## Building and Running the Model

To build the model under Linux:

1. Download and extract the archive.
2. Change directory to the code directory:
   ```
   cd code
   ```
3. Compile the code by typing:
   ```
   make
   ```
4. Run the model with:
   ```
   ./simulation
   ```

The model in its default setting will start up. The model is written in ANSI C and should work with every C compiler.

---

2025-05-27 – Standardized to Markdown
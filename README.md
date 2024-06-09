## Multi-modal on push-T
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Multi-modality behavior</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/multi_modal.png" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Video</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/multi_modal.gif" alt="flow" width="300"/> 
  </div> 
</div>

## PushT-state-policy
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Diffusion Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/pusht_state_diffusion.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/pusht_state_flow.gif" alt="flow" width="300"/> 
  </div> 
</div>

## PushT-visual-policy
**Inference advantage**
- FlowPolicy + 1-step generation: 0.95~1 reward (max 1).
- DiffusionPolicy + 1-step generation: 0 reward.

Self-contained python codes are available: [FlowPolicy](https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/flow_policy_vision_pusht_demo.py), [DiffusionPolicy](https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/diffusion_policy_vision_pusht_demo.py)
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Diffusion Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/pusht_visual_diffusion.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_pusht_results/pusht_visual_flow.gif" alt="flow" width="300"/> 
  </div> 
</div>

## Robomimic-state-policy
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Flow Policy (lift) </em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/lift_ph_state.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy (square) </em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/square_ph_state.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy (transport) </em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/transport_ph_state.gif" alt="flow" width="300"/>
</div>


## Robomimic-Square-visual-ph-policy
### Videos
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Diffusion Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/square_ph_visual_diffusion.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/square_ph_visual_flow.gif" alt="flow" width="300"/> 
  </div> 
</div>

### Success rate vs. Inference NFE

Despite variations, both were able to reach **0.94** success rate when NFE = 100 (last point), as reported based on policy rollout during training.

<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/rate_vs_steps_square.png" alt="flow" width="500"/> 
  </div> 
</div>


## Robomimic-Transport-visual-ph-policy
### Videos
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Diffusion Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/transport_ph_visual_diffusion.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/transport_ph_visual_flow.gif" alt="flow" width="300"/> 
  </div> 
</div>

### Success rate vs. Inference NFE

Despite variations, both were able to reach **0.94** success rate when NFE = 100 (last point), as reported based on policy rollout during training.

<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/rate_vs_steps_transport.png" alt="flow" width="500"/> 
  </div> 
</div>

## Robomimic-Tool hang-visual-ph--policy
### Videos
<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <p><em>Diffusion Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/tool_hang_ph_visual_diffusion.gif" alt="flow" width="300"/> 
  </div> 
  <div class="image-item"> 
    <p><em>Flow Policy</em></p> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/tool_hang_ph_visual_flow.gif" alt="flow" width="300"/> 
  </div> 
</div>

### Success rate vs. Inference NFE

Despite variations, both were able to reach **0.92** success rate when NFE = 100 (last point), as reported based on policy rollout during training.

<div class="image-container" style="display: flex; align-items: center;"> 
  <div class="image-item" style="margin-right: 20px;"> 
    <img src="https://github.com/chen-xu-tri/test/blob/main/simul_robomimic_results/rate_vs_steps_tool_hang_updated.png" alt="flow" width="500"/> 
  </div> 
</div>
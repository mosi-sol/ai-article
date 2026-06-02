```
                        [ INPUT EMISSION STIMULUS (Σ) ]
                                       │
                                       ▼
                       [ L2 NORMALIZATION HYPERSPHERE ]
                     (Forces Input to Unit Vector Length)
                                       │
                ┌──────────────────────┴──────────────────────┐
                ▼ Scalar Score > τ                            ▼ Scalar Score ≤ τ
      [ FIRE REFLEX NODE ]                          [ BYPASS NODE REGISTRY ]
  (Memory Element Activated)                       (Zero Token Overhead / Silent)
                │
                ▼
   [ PROMPT PAYLOAD INJECTION ]
  (Injected into Agent Context)
                │
                ▼
   [ ENVIRONMENT TASK EVALUATION ]
                │
        ┌───────┴───────┐
        ▼ Task Success  ▼ Task Failure / User Override
     [ ATTRACT VECTOR ]               [ REPEL VECTOR ]
  (Pulls node memory closer        (Pushes node memory away
   to stimulus profile)             from stimulus profile)
                │                                │
                └───────────────┬────────────────┘
                                │
                                ▼
               [ PROJECT BACK TO HYPERSPHERE ]
                (Enforces Unit Vector Length)

```

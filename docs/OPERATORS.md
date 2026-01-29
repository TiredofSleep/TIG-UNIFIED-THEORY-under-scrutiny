# TIG Operators

**Complete Reference — Version 3.0**

---

## Overview

TIG defines 10 base operators (0-9) plus the Ω̂ (omega-hat) unification operator. These operators represent fundamental actions that systems can take to maintain or restore coherence.

Operators are:
- **Composable**: Can be combined in sequences
- - **Reversible**: Most have inverse operations
  - - **Scale-invariant**: Apply at any system level
   
    - ---

    ## Base Operators (0-9)

    ### Operator 0: Void

    **Symbol**: `∅` or `0`
    **Name**: Void
    **Function**: Null state, initialization, emptiness

    **Semantics:**
    - Return to zero state
    - - Clear all buffers
      - - Initialize from nothing
        - - Represents potential before actualization
         
          - **Compute expression:**
          - ```
            void() → null
            void(x) → x = 0
            ```

            **Use cases:**
            - System cold start
            - - Memory wipe
              - - State reset to known-good
               
                - **Inverse**: None (void is the ground state)
               
                - ---

                ### Operator 1: Lattice

                **Symbol**: `⊞` or `1`
                **Name**: Lattice
                **Function**: Structure formation, grid creation, spatial ordering

                **Semantics:**
                - Create organized structure from chaos
                - - Establish regular patterns
                  - - Define boundaries and positions
                    - - Scaffold for future operations
                     
                      - **Compute expression:**
                      - ```
                        lattice(nodes) → structured_graph(nodes)
                        lattice(data) → indexed_structure(data)
                        ```

                        **Use cases:**
                        - Cluster topology setup
                        - - Index construction
                          - - Network mesh formation
                            - - Schema definition
                             
                              - **Inverse**: Operator 6 (Chaos)
                             
                              - ---

                              ### Operator 2: Counter

                              **Symbol**: `#` or `2`
                              **Name**: Counter
                              **Function**: Increment, measurement, enumeration

                              **Semantics:**
                              - Add one to count
                              - - Measure quantity
                                - - Track occurrences
                                  - - Discrete progression
                                   
                                    - **Compute expression:**
                                    - ```
                                      count(x) → x + 1
                                      count(set) → |set|
                                      ```

                                      **Use cases:**
                                      - Metrics collection
                                      - - Reference counting
                                        - - Heartbeat tracking
                                          - - Sequence numbering
                                           
                                            - **Inverse**: Decrement (implicit)
                                           
                                            - ---

                                            ### Operator 3: Progress

                                            **Symbol**: `→` or `3`
                                            **Name**: Progress
                                            **Function**: Forward movement, advancement, evolution

                                            **Semantics:**
                                            - Move from state A to state B
                                            - - Time's arrow
                                              - - Irreversible advancement
                                                - - Growth and development
                                                 
                                                  - **Compute expression:**
                                                  - ```
                                                    progress(state, delta) → next_state
                                                    progress(task) → task.advance()
                                                    ```

                                                    **Use cases:**
                                                    - Job execution
                                                    - - State machine transitions
                                                      - - Version upgrades
                                                        - - Data pipeline stages
                                                         
                                                          - **Inverse**: Rollback (not exact inverse — progress may be irreversible)
                                                         
                                                          - ---

                                                          ### Operator 4: Collapse

                                                          **Symbol**: `↓` or `4`
                                                          **Name**: Collapse
                                                          **Function**: State reduction, decision, measurement

                                                          **Semantics:**
                                                          - Many possibilities → one actuality
                                                          - - Superposition → definite state
                                                            - - Aggregation to single value
                                                              - - Decision point
                                                               
                                                                - **Compute expression:**
                                                                - ```
                                                                  collapse(possibilities) → selected_one
                                                                  collapse(distribution) → sample
                                                                  collapse(options, criteria) → best_option
                                                                  ```

                                                                  **Use cases:**
                                                                  - Load balancer selection
                                                                  - - Consensus finalization
                                                                    - - Query result aggregation
                                                                      - - Feature flag resolution
                                                                       
                                                                        - **Inverse**: Operator 6 (Chaos) — but information is lost in collapse
                                                                       
                                                                        - ---

                                                                        ### Operator 5: Balance

                                                                        **Symbol**: `⚖` or `5`
                                                                        **Name**: Balance
                                                                        **Function**: Equilibrium seeking, fairness, homeostasis

                                                                        **Semantics:**
                                                                        - Restore equal distribution
                                                                        - - Find stable midpoint
                                                                          - - Counteract imbalance
                                                                            - - Maintain steady state
                                                                             
                                                                              - **Compute expression:**
                                                                              - ```
                                                                                balance(loads) → redistribute(loads, equal)
                                                                                balance(accounts) → reconcile(accounts)
                                                                                ```

                                                                                **Use cases:**
                                                                                - Load balancing
                                                                                - - Resource allocation
                                                                                  - - Queue leveling
                                                                                    - - Rate limiting
                                                                                     
                                                                                      - **Inverse**: Imbalance (not a defined operator — balance seeks to undo imbalance)
                                                                                     
                                                                                      - ---

                                                                                      ### Operator 6: Chaos

                                                                                      **Symbol**: `☆` or `6`
                                                                                      **Name**: Chaos
                                                                                      **Function**: Entropy injection, randomization, disorder

                                                                                      **Semantics:**
                                                                                      - Break existing structure
                                                                                      - - Introduce randomness
                                                                                        - - Test resilience
                                                                                          - - Prevent stagnation
                                                                                           
                                                                                            - **Compute expression:**
                                                                                            - ```
                                                                                              chaos(structure) → randomize(structure)
                                                                                              chaos(system) → inject_fault(system)
                                                                                              ```

                                                                                              **Use cases:**
                                                                                              - Chaos engineering (kill random pods)
                                                                                              - - Fuzzing
                                                                                                - - Shuffle operations
                                                                                                  - - Entropy generation
                                                                                                   
                                                                                                    - **Inverse**: Operator 1 (Lattice)
                                                                                                   
                                                                                                    - ---
                                                                                                    
                                                                                                    ### Operator 7: Harmony
                                                                                                    
                                                                                                    **Symbol**: `♪` or `7`
                                                                                                    **Name**: Harmony
                                                                                                    **Function**: Resonance alignment, synchronization, consonance
                                                                                                    
                                                                                                    **Semantics:**
                                                                                                    - Bring disparate elements into alignment
                                                                                                    - - Synchronize frequencies
                                                                                                      - - Achieve mutual reinforcement
                                                                                                        - - Coherent oscillation
                                                                                                         
                                                                                                          - **Compute expression:**
                                                                                                          - ```
                                                                                                            harmony(clocks) → synchronize(clocks)
                                                                                                            harmony(replicas) → consensus(replicas)
                                                                                                            ```
                                                                                                            
                                                                                                            **Use cases:**
                                                                                                            - Clock synchronization (NTP, PTP)
                                                                                                            - - Replica convergence
                                                                                                              - - Cache coherence
                                                                                                                - - Distributed consensus
                                                                                                                 
                                                                                                                  - **Inverse**: Desynchronization (partial inverse via chaos)
                                                                                                                 
                                                                                                                  - ---
                                                                                                                  
                                                                                                                  ### Operator 8: Breath
                                                                                                                  
                                                                                                                  **Symbol**: `∿` or `8`
                                                                                                                  **Name**: Breath
                                                                                                                  **Function**: Oscillation, cycles, rhythmic alternation
                                                                                                                  
                                                                                                                  **Semantics:**
                                                                                                                  - Inhale/exhale pattern
                                                                                                                  - - Periodic expansion and contraction
                                                                                                                    - - Heartbeat rhythm
                                                                                                                      - - Wave-like behavior
                                                                                                                       
                                                                                                                        - **Compute expression:**
                                                                                                                        - ```
                                                                                                                          breath(system) → oscillate(system, period)
                                                                                                                          breath(buffer) → fill_then_flush(buffer)
                                                                                                                          ```
                                                                                                                          
                                                                                                                          **Use cases:**
                                                                                                                          - Garbage collection cycles
                                                                                                                          - - Batch processing windows
                                                                                                                            - - Health check intervals
                                                                                                                              - - Autoscaling oscillation
                                                                                                                               
                                                                                                                                - **Inverse**: Flatline (not desirable — systems should breathe)
                                                                                                                               
                                                                                                                                - ---
                                                                                                                                
                                                                                                                                ### Operator 9: Reset
                                                                                                                                
                                                                                                                                **Symbol**: `↺` or `9`
                                                                                                                                **Name**: Reset
                                                                                                                                **Function**: Return to origin, restart, reboot
                                                                                                                                
                                                                                                                                **Semantics:**
                                                                                                                                - Go back to known-good state
                                                                                                                                - - Clear accumulated drift
                                                                                                                                  - - Fresh start
                                                                                                                                    - - Different from void — reset returns to *defined* initial state, not emptiness
                                                                                                                                     
                                                                                                                                      - **Compute expression:**
                                                                                                                                      - ```
                                                                                                                                        reset(system) → system.initial_state
                                                                                                                                        reset(counter) → counter = initial_value
                                                                                                                                        ```
                                                                                                                                        
                                                                                                                                        **Use cases:**
                                                                                                                                        - System reboot
                                                                                                                                        - - Transaction rollback
                                                                                                                                          - - Session termination
                                                                                                                                            - - Circuit breaker reset
                                                                                                                                             
                                                                                                                                              - **Inverse**: None (reset establishes new baseline)
                                                                                                                                             
                                                                                                                                              - ---
                                                                                                                                              
                                                                                                                                              ## The Ω̂ Operator (Omega-Hat)
                                                                                                                                              
                                                                                                                                              **Symbol**: `Ω̂`
                                                                                                                                              **Name**: Unification / Coherence Keeper
                                                                                                                                              **Function**: Meta-operation, orchestration, coherence maintenance
                                                                                                                                              
                                                                                                                                              ### Semantics
                                                                                                                                              
                                                                                                                                              Ω̂ is not a single operation but a meta-operator that:
                                                                                                                                              1. **Observes**: Monitors S* across all nodes/scales
                                                                                                                                              2. 2. **Decides**: Determines which operators to invoke
                                                                                                                                                 3. 3. **Orchestrates**: Coordinates multi-node responses
                                                                                                                                                    4. 4. **Maintains**: Keeps S* above threshold T*
                                                                                                                                                      
                                                                                                                                                       5. ### Ω̂ as Operator Selector
                                                                                                                                                      
                                                                                                                                                       6. ```
                                                                                                                                                          Ω̂(system_state) → operator_sequence

                                                                                                                                                          Example:
                                                                                                                                                            If S* dropping due to imbalance:
                                                                                                                                                              Ω̂ → [5 (balance), 7 (harmony)]

                                                                                                                                                            If S* dropping due to accumulated errors:
                                                                                                                                                              Ω̂ → [9 (reset)] or [4 (collapse), 1 (lattice)]

                                                                                                                                                            If S* stable but stagnant:
                                                                                                                                                              Ω̂ → [6 (chaos), 3 (progress)]
                                                                                                                                                          ```
                                                                                                                                                          
                                                                                                                                                          ### The Coherence Keeper Archetype
                                                                                                                                                          
                                                                                                                                                          Ω̂ is associated with Archetype 12 (Coherence Keeper):
                                                                                                                                                          - Only archetype that operates on other archetypes
                                                                                                                                                          - - Maintains meta-stability
                                                                                                                                                            - - Intervenes when normal archetype transitions fail
                                                                                                                                                             
                                                                                                                                                              - ### Ω̂ Properties
                                                                                                                                                             
                                                                                                                                                              - - **Non-local**: Acts on entire system, not single nodes
                                                                                                                                                                - - **Reflective**: Can observe its own operations
                                                                                                                                                                  - - **Conservative**: Prefers minimal intervention
                                                                                                                                                                    - - **Predictive**: Anticipates coherence degradation (in advanced implementations)
                                                                                                                                                                     
                                                                                                                                                                      - ---
                                                                                                                                                                      
                                                                                                                                                                      ## Operator Composition
                                                                                                                                                                      
                                                                                                                                                                      Operators can be composed in sequences:
                                                                                                                                                                      
                                                                                                                                                                      ### Notation
                                                                                                                                                                      
                                                                                                                                                                      ```
                                                                                                                                                                      Op1 · Op2 · Op3  (sequential application)
                                                                                                                                                                      Op1 ⊗ Op2       (parallel application)
                                                                                                                                                                      Op1 | Op2       (conditional: Op1 if condition, else Op2)
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      ### Common Patterns
                                                                                                                                                                      
                                                                                                                                                                      **Reset-Lattice-Progress** (recovery sequence):
                                                                                                                                                                      ```
                                                                                                                                                                      9 · 1 · 3
                                                                                                                                                                      Reset to known state, establish structure, advance
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      **Chaos-Balance-Harmony** (resilience test):
                                                                                                                                                                      ```
                                                                                                                                                                      6 · 5 · 7
                                                                                                                                                                      Inject disorder, rebalance, verify alignment
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      **Collapse-Counter-Progress** (decision loop):
                                                                                                                                                                      ```
                                                                                                                                                                      (4 · 2 · 3)*
                                                                                                                                                                      Repeatedly: decide, measure, advance
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      ---
                                                                                                                                                                      
                                                                                                                                                                      ## Operator Algebra
                                                                                                                                                                      
                                                                                                                                                                      ### Identity
                                                                                                                                                                      
                                                                                                                                                                      ```
                                                                                                                                                                      0 · X = X · 0 = X  (void is identity for most operations)
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      ### Inverses
                                                                                                                                                                      
                                                                                                                                                                      ```
                                                                                                                                                                      1 · 6 ≈ identity  (lattice then chaos returns to ~void)
                                                                                                                                                                      6 · 1 ≈ identity  (chaos then lattice creates new structure)
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      Note: Not exact inverses due to information loss.
                                                                                                                                                                      
                                                                                                                                                                      ### Idempotence
                                                                                                                                                                      
                                                                                                                                                                      ```
                                                                                                                                                                      5 · 5 = 5  (balance is idempotent)
                                                                                                                                                                      9 · 9 = 9  (reset is idempotent)
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      ### Non-Commutativity
                                                                                                                                                                      
                                                                                                                                                                      Most operators do not commute:
                                                                                                                                                                      ```
                                                                                                                                                                      3 · 4 ≠ 4 · 3  (progress then collapse ≠ collapse then progress)
                                                                                                                                                                      ```
                                                                                                                                                                      
                                                                                                                                                                      ---
                                                                                                                                                                      
                                                                                                                                                                      ## Open Questions
                                                                                                                                                                      
                                                                                                                                                                      1. Is this operator set **complete**? Can all coherence-maintaining operations be expressed?
                                                                                                                                                                      2. 2. What is the **minimal** operator set? Are some operators derivable from others?
                                                                                                                                                                         3. 3. Is there a **group structure**? What are the symmetries?
                                                                                                                                                                            4. 4. How do operators relate to **category theory** morphisms?
                                                                                                                                                                              
                                                                                                                                                                               5. ---
                                                                                                                                                                              
                                                                                                                                                                               6. **Author**: Brayden Sanders, 7Site LLC
                                                                                                                                                                               7. **Status**: Frozen for validation
                                                                                                                                                                               8. **Version**: 3.0

<template>
    <div class="container-fluid custom-top-buffer">
        <h1>Administration and Scoring</h1>
        <table class="table table-striped">
            <tr class="table-dark">
                <th>#</th>
                <th>Test Item</th>
                <th colspan="3">Score</th>
            </tr>
            <tr class="table-info">
                <th></th>
                <th>Motor</th>
                <th>0</th>
                <th>1</th>
                <th>2</th> 
            </tr>
            <!-- WARNING: Need to rename the NAME portion of the radio buttons
                    give unique identifier to it eg: bicep-reflex-mtr -->
            <tr>
                <td></td>
                <td>Biceps Reflex</td>
                <td>
                    <input class="form-check-input" type="radio" name="biceps-reflex-mtr" value=0 v-model="bicepsReflexMtr">
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="biceps-reflex-mtr" value=1 >
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="biceps-reflex-mtr" value=2 >
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Triceps Reflex</td>
                <td>
                    <input class="form-check-input" type="radio" name="triceps-reflex-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="triceps-reflex-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="triceps-reflex-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Retraction</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-retraction-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-retraction-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-retraction-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Elevation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-elevation-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-elevation-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-elevation-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Adduction/Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Hand to Lumbar Spine</td>
                <td>
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion 0&deg; - 90&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation-Supination, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction 0&deg; - 90&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion 90&deg; - 180&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation-Supination, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Normal Reflex Activity</td>
                <td>
                    <input class="form-check-input" type="radio" name="normal-reflex-activity-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="normal-reflex-activity-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="normal-reflex-activity-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Stability, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion/Extension, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Stability, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion/Extension, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Circumduction</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-circumduction-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-circumduction-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-circumduction-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Mass Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Mass Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-extension-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-extension-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-mass-extension-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Distal Finger Grasp (Hook Grasp)</td>
                <td>
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Thumb Adduction Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Thumb to Index Finger Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Cylindrical Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="cylindrical-grasp-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="cylindrical-grasp-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="cylindrical-grasp-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Spherical Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="spherical-grasp-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="spherical-grasp-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="spherical-grasp-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Tremor</td>
                <td>
                    <input class="form-check-input" type="radio" name="tremor-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="tremor-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="tremor-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Dysmetria</td>
                <td>
                    <input class="form-check-input" type="radio" name="dysmetria-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="dysmetria-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="dysmetria-mtr" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Speed</td>
                <td>
                    <input class="form-check-input" type="radio" name="speed-mtr" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="speed-mtr" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="speed-mtr" value=2>
                </td>
            </tr>
            <tr class="table-info">
                <th></th>
                <th>Sensation</th>
                <th>0</th>
                <th>1</th>
                <th>2</th> 
            </tr>
            <tr>
                <td></td>
                <td>Light Touch - Upper Arm, Forearm</td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm-snt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Light Touch - Palmar Surface of Hand</td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand-snt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Shoulder</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-shoulder-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-shoulder-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-shoulder-snt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Elbow</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-elbow-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-elbow-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-elbow-snt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Wrist</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-wrist-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-wrist-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-wrist-snt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Thumb</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-thumb-snt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-thumb-snt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-thumb-snt" value=2>
                </td>
            </tr>
            <tr class="table-info">
                <th></th>
                <th>Passive Joint Motion</th>
                <th>0</th>
                <th>1</th>
                <th>2</th> 
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion (0&deg; - 180 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="external-rotation-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="internal-rotation-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-extension-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-flexion-pjt" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension-pjt" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension-pjt" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-extension-pjt" value=2>
                </td>
            </tr>
            <tr class="table-info">
                <th></th>
                <th>Joint Pain</th>
                <th>0</th>
                <th>1</th>
                <th>2</th> 
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion (0&deg; - 180 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="external-rotation-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="internal-rotation-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-extension-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-flexion-jp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension-jp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension-jp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-extension-jp" value=2>
                </td>
            </tr>
        </table>
    </div>
</template>
<script>
export default {
    name:"Main",
    data(){
        return{
            test:"test",
            bicepsReflexMtr:null,
            tricepsReflexMtr:null,
            shoulderRetractionMtr:null,
            shoulderElevationMtr:null,
            shoulderAbductionMtr:null,
            shoulderExternalRotationMtr:null,
            elbowFlexionMtr:null,
            forearmSupinationMtr:null,
            shoulderAdductionInternalRotationMtr:null,
            elbowExtensionMtr:null,
            forearmPronationMtr:null,
            handToLumbarSpineMtr:null,
            shoulderFlexion090ElbowExtendedMtr:null,
            forearmPronationSupinationElbowAt90Mtr:null,
            shoulderAbduction090ElbowExtendedMtr:null,
            shoulderFlexion90180ElbowExtendedMtr:null,
            forearmPronationSupinationElbowExtendedMtr:null,
            normalReflexActivityMtr:null,
            wristStabilityElbowAt90Mtr:null,
            wristFlexionExtensionElbowAt90Mtr:null,
            wristStabilityElbowExtendedMtr:null,
            wristFlexionExtensionElbowExtendedMtr:null,
            wristCircumductionMtr:null,
            fingersMassFlexionMtr:null,
            fingersMassExtensionMtr:null,
            distalFingerGraspHookGraspMtr:null,
            thumbAdductionGraspMtr:null,
            thumbToIndexFingerGraspMtr:null,
            cylindricalGraspMtr:null,
            sphericalGraspMtr:null,
            tremorMtr:null,
            dysmetriaMtr:null,
            speedMtr:null,
            lightTouchUpperArmForearmSnt:null,
            lightTouchPalmarSurfaceOfHandSnt:null,
            positionShoulderSnt:null,
            positionElbowSnt:null,
            positionWristSnt:null,
            positionThumbSnt:null,
            shoulderFlexion0180Pjt:null,
            shoulderAbduction090Pjt:null,
            externalRotationPjt:null,
            internalRotationPjt:null,
            elbowFlexionPjt:null,
            elbowExtensionPjt:null,
            forearmPronationPjt:null,
            forearmSupinationPjt:null,
            wristFlexionPjt:null,
            wristExtensionPjt:null,
            fingersFlexionPjt:null,
            fingersExtensionPjt:null,
            shoulderFlexion0180Jp:null,
            shoulderAbduction090Jp:null,
            externalRotationJp:null,
            internalRotationJp:null,
            elbowFlexionJp:null,
            elbowExtensionJp:null,
            forearmPronationJp:null,
            forearmSupinationJp:null,
            wristFlexionJp:null,
            wristExtensionJp:null,
            fingersFlexionJp:null,
            fingersExtensionJp:null,
        }
    }
}
</script>
<style>
    .custom-radio{
        vertical-align: middle;
        margin:0;
    }
</style>

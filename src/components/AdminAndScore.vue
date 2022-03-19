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
            <tr>
                <td></td>
                <td>Biceps Reflex</td>
                <td>
                    <input class="form-check-input" type="radio" name="biceps-reflex" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="biceps-reflex" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="biceps-reflex" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Triceps Reflex</td>
                <td>
                    <input class="form-check-input" type="radio" name="triceps-reflex" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="triceps-reflex" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="triceps-reflex" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Retraction</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-retraction" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-retraction" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-retraction" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Elevation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-elevation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-elevation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-elevation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-external-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Adduction/Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-adduction-internal-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Hand to Lumbar Spine</td>
                <td>
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="hand-to-lumbar-spine" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion 0&deg; - 90&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-90-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation-Supination, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-at-90" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction 0&deg; - 90&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Flexion 90&deg; - 180&deg;, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-90-180-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation-Supination, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation-supination-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Normal Reflex Activity</td>
                <td>
                    <input class="form-check-input" type="radio" name="normal-reflex-activity" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="normal-reflex-activity" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="normal-reflex-activity" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Stability, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-at-90" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion/Extension, Elbow at 90&deg;</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-at-90" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Stability, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-stability-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion/Extension, Elbow Extended</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion-extension-elbow-extended" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Circumduction</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-circumduction" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-circumduction" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-circumduction" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Mass Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-mass-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Mass Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-mass-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-mass-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Distal Finger Grasp (Hook Grasp)</td>
                <td>
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="distal-finger-grasp-hook-grasp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Thumb Adduction Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="thumb-adduction-grasp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Thumb to Index Finger Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="thumb-to-index-finger-grasp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Cylindrical Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="cylindrical-grasp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="cylindrical-grasp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="cylindrical-grasp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Spherical Grasp</td>
                <td>
                    <input class="form-check-input" type="radio" name="spherical-grasp" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="spherical-grasp" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="spherical-grasp" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Tremor</td>
                <td>
                    <input class="form-check-input" type="radio" name="tremor" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="tremor" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="tremor" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Dysmetria</td>
                <td>
                    <input class="form-check-input" type="radio" name="dysmetria" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="dysmetria" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="dysmetria" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Speed</td>
                <td>
                    <input class="form-check-input" type="radio" name="speed" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="speed" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="speed" value=2>
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
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="light-touch-upper-arm-forearm" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Light Touch - Palmar Surface of Hand</td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="light-touch-palmar-surface-of-hand" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Shoulder</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-shoulder" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-shoulder" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-shoulder" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Elbow</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-elbow" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-elbow" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-elbow" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Wrist</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-wrist" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-wrist" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-wrist" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Position - Thumb</td>
                <td>
                    <input class="form-check-input" type="radio" name="position-thumb" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="position-thumb" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="position-thumb" value=2>
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
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="external-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="internal-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-extension" value=2>
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
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-flexion-0-180" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Shoulder Abduction (0&deg; - 90 &deg;)</td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="shoulder-abduction-0-90" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>External Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="external-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="external-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Internal Rotation</td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="internal-rotation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="internal-rotation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Elbow Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="elbow-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="elbow-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Pronation</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-pronation" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Forearm Supination</td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="forearm-supination" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="forearm-supination" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Wrist Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="wrist-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="wrist-extension" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Flexion</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-flexion" value=2>
                </td>
            </tr>
            <tr>
                <td></td>
                <td>Fingers Extension</td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension" value=0>
                </td>
                <td>
                    <input class="form-check-input" type="radio" name="fingers-extension" value=1>
                </td>
                <td>    
                    <input class="form-check-input" type="radio" name="fingers-extension" value=2>
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
            test:"test"
        }
    }
}
</script>
<style>
    .custom-radio{
        vertical-align: middle;margin:0;
    }
</style>

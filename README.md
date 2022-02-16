# AI4WFSSandbox
This is meant to be a simplified simulation of adaptive segmented telescope to test AI reconstruction capabilities. 

For now this is meant as a simple monochromatic simulation which will produce an image of the zernike phase contrast sensor. Simple camera effect are simulated (RON). The image will be fed to a AI. The AI will attempt to reconstruct the wavefront and the correction applied. The test should run a number of iteration and then evaluate if the telescope state has improved. 

This is more of a proof of concept for now so if you end up here thinking you found gold, please hold your horses, this is merely the work of a random person with a silly idea.

Required external packages:
Poppy: https://github.com/spacetelescope/poppy
scikit-learn: https://scikit-learn.org/stable/index.html

Optionnal external packages:
Pyxel: https://esa.gitlab.io/pyxel/

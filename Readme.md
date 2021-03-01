---


---

<h1 id="dog-breed-identification-project">Dog Breed identification Project</h1>
<p>This is the dog breed identification projecy submission by <strong>Alain Ramirez Martinez</strong>. This project is made in an ipython notebook which contains the main project codes and results.</p>
<h1 id="requirements">Requirements</h1>
<p>Most of the code was implemented in Udacity workspace. The main libraries used for this project are:</p>
<ul>
<li><a href="https://opencv.org/">OpenCV</a></li>
<li>Pytorch</li>
<li><a href="https://pypi.org/project/tqdm/">TQDM</a> (Fast, Extensible Progress Meter)</li>
<li>VGG16 pre-trained model</li>
<li>Model from Scratch from <a href="https://medium.com/analytics-vidhya/classification-of-dog-breed-using-deep-learning-343f98ebebf0">here</a></li>
<li>Alexnet pre-trained model (proposal)</li>
<li>Resnet18 pre-trained model (report)</li>
</ul>
<p>The following library was implementd in a personal computer (Intel Corei5 6th gen, 32GB RAM) with <a href="https://www.anaconda.com/">Anaconda distribution</a> because it is not supported in the workspace.</p>
<ul>
<li>Learning rate finder (See: <a href="https://github.com/davidtvs/pytorch-lr-finder">https://github.com/davidtvs/pytorch-lr-finder</a>)</li>
</ul>
<p>The following torchvision transform was implemented in the same personal computer because is not supported in the workspace:</p>
<ul>
<li>Transform.RandomPerspective(0.5,0.5,2,0)</li>
</ul>
<h2 id="extra-files-included-in-this-project">Extra files included in this project</h2>
<p>The following files are included as a probe of other tests that were made for this project.</p>
<ul>
<li>dog para lr.ipynb</li>
<li>algorithm.ppt</li>
</ul>
<h2 id="repository">Repository</h2>
<p>The original Udacity project instructions can be found <a href="https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification">here</a>.</p>
<ul>
<li>The dog dataset can be downloaded from this <a href="https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip">link</a></li>
<li>The human dataset can be downloaded from this <a href="https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip">link</a></li>
</ul>
<h2 id="achievements">Achievements</h2>
<p>The Model from scratch can achieve 16% of accuracy in just 10 epochs. That was accomplished after some tests with different learning rate and data augmentation.<br>
The Model from scratch can achieve 20% of accuracy in 20 epochs. That was accomplished after some tests with different learning rate and data augmentation. Unfortunatly there is no probe of this because it was made in a personal computer without random seed. Next tests could not replicate that result.</p>


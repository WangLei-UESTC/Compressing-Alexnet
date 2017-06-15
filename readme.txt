Compressing Alexnet using k-means and improved k-means
Model_pruning.py:Pruning only,just set some small weights to zeros,do not change the size of the network;
caffemodel_kmeans_quantization.py:weights sharing only,you can change the path to your caffemodel.and choose two weights sharing algorithms;
caffemodel_kmeans_accuracy.py:recover model from compressed model,.npz;
alexnet_caffmodel_kweight.npz:model parameters after compression;
alexnet_kmeansk.caffemodel:model from caffemodel_kmeans_accuracy.py,standard caffemodel.because the fileis too big,do not upload here,you can generate it yourself.
data:there are some image set which can be used directely.some from imagenet and others from internet
refer to :
	https://github.com/BVLC/caffe
	https://github.com/michaelchughes
	https://github.com/yuanyuanli85/CaffeModelCompression
	
	

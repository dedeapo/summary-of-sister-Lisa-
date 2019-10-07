inpainting with pre-trained GAN in a feedback manner

checkpoint: ./checkpoint
test_img_path: ./test
test_result_path: ./completions (automatically created)

size:64

this can load either .jpg or .png images without modification

trained in a identic mask: center, half ... which can be changed
 in function:complete in model.py

the batchsize of test can be any int number

# Match_Template
Find a template in a image

模板匹配是在图像中寻找目标的方法之一

通过在输入图像上滑动图像块对实际的图像块和输入图像进行匹配


在OpenCv和EmguCv中支持以下6种对比方式：
    CV_TM_SQDIFF 平方差匹配法：该方法采用平方差来进行匹配；最好的匹配值为0；匹配越差，匹配值越大。
    CV_TM_CCORR 相关匹配法：该方法采用乘法操作；数值越大表明匹配程度越好。
    CV_TM_CCOEFF 相关系数匹配法：1表示完美的匹配；-1表示最差的匹配。
    CV_TM_SQDIFF_NORMED 归一化平方差匹配法
    CV_TM_CCORR_NORMED 归一化相关匹配法
    CV_TM_CCOEFF_NORMED 归一化相关系数匹配法

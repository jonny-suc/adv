========================
PC版按科室找医生页
========================

.. list-table:: 版本修改记录
   :widths: 10 10 40 
   :header-rows: 1

   * - 修改人
     - 修改日期
     - 修改内容
   * - jonny
     - 2019/7/29
     - 创建


PC版按科室找医生页A级客户通栏广告位1
===========================================

::

  广告位key:adpp_seekDoctorDpt_1



----------
请求实例
----------

.. list-table:: 
   :widths: 18 40
   :header-rows: 1

   * - 名称
     - 值
   * - tk
     - c8cde65c479894e21d62e23b8d24455d
   * - ts
     - 1520600716
   * - adpp_id
     - adpp_seekDoctorDpt_1
   * - userid
     - 4370587
   * - ext_params
     - {"data_type":"json","refer":"www","mid":5032,"new_cateid":121,"ip":"27.43.95.0","hid":0,"site":"mingyihui","url":"","ddid":0}




-------------
返回实例
-------------

.. code-block:: JAVASCRIPT

    {
      "errcode": 0,
      "msg": "成功",
      "data": {
        "adpp_type": "0",
        "adv_list": [
          {
            "id": "7",
            "sign": "adpp_index_1_7",
            "ad_name": "test1",
            "sort_num": "1",
            "ad_content": [
              {
                "ad_content_id": "15",
                "content_type": "1",
                "ad_url": "http://www.baidu.com",
                "ad_content": "/upload/adv/20190729/1555103423.jpg"
              }
            ]
          }
        ]
      }
    }
## 效果图：
    ![](/icon1.png)
    ![](/icon2.png)

## 使用

1. 使用方法参考com.hotel.calendar.MainActivity：
```Java

    http://zf.lbjet.com/mobile/index.php?act=houses&op=house_calendar&month=2017-03&half_a_year=1&house_id=1524
    private String testStr = "{\"code\":200,\"datas\":[{\"month\":\"2017-03\",\"days\":[{\"num\":\"1\",\"date\":\"2017-03-1\",\"week\":\"3\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-03-2\",\"week\":\"4\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-03-3\",\"week\":\"5\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-03-4\",\"week\":\"6\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-03-5\",\"week\":\"0\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-03-6\",\"week\":\"1\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-03-7\",\"week\":\"2\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-03-8\",\"week\":\"3\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-03-9\",\"week\":\"4\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-03-10\",\"week\":\"5\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-03-11\",\"week\":\"6\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-03-12\",\"week\":\"0\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-03-13\",\"week\":\"1\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-03-14\",\"week\":\"2\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-03-15\",\"week\":\"3\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-03-16\",\"week\":\"4\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-03-17\",\"week\":\"5\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-03-18\",\"week\":\"6\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-03-19\",\"week\":\"0\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-03-20\",\"week\":\"1\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-03-21\",\"week\":\"2\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-03-22\",\"week\":\"3\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-03-23\",\"week\":\"4\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-03-24\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-03-25\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-03-26\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-03-27\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-03-28\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-03-29\",\"week\":\"3\",\"price\":398,\"is_buy\":\"0\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-03-30\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"31\",\"date\":\"2017-03-31\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]},{\"month\":\"2017-4\",\"days\":[{\"num\":\"1\",\"date\":\"2017-4-1\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-4-2\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-4-3\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-4-4\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-4-5\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-4-6\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-4-7\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-4-8\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-4-9\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-4-10\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-4-11\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-4-12\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-4-13\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-4-14\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-4-15\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-4-16\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-4-17\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-4-18\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-4-19\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-4-20\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-4-21\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-4-22\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-4-23\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-4-24\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-4-25\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-4-26\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-4-27\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-4-28\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-4-29\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-4-30\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]},{\"month\":\"2017-5\",\"days\":[{\"num\":\"1\",\"date\":\"2017-5-1\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-5-2\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-5-3\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-5-4\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-5-5\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-5-6\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-5-7\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-5-8\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-5-9\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-5-10\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-5-11\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-5-12\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-5-13\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-5-14\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-5-15\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-5-16\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-5-17\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-5-18\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-5-19\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-5-20\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-5-21\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-5-22\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-5-23\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-5-24\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-5-25\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-5-26\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-5-27\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-5-28\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-5-29\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-5-30\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"31\",\"date\":\"2017-5-31\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]},{\"month\":\"2017-6\",\"days\":[{\"num\":\"1\",\"date\":\"2017-6-1\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-6-2\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-6-3\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-6-4\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-6-5\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-6-6\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-6-7\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-6-8\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-6-9\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-6-10\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-6-11\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-6-12\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-6-13\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-6-14\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-6-15\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-6-16\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-6-17\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-6-18\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-6-19\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-6-20\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-6-21\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-6-22\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-6-23\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-6-24\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-6-25\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-6-26\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-6-27\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-6-28\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-6-29\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-6-30\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]},{\"month\":\"2017-7\",\"days\":[{\"num\":\"1\",\"date\":\"2017-7-1\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-7-2\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-7-3\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-7-4\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-7-5\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-7-6\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-7-7\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-7-8\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-7-9\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-7-10\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-7-11\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-7-12\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-7-13\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-7-14\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-7-15\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-7-16\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-7-17\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-7-18\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-7-19\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-7-20\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-7-21\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-7-22\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-7-23\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-7-24\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-7-25\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-7-26\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-7-27\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-7-28\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-7-29\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-7-30\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"31\",\"date\":\"2017-7-31\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]},{\"month\":\"2017-8\",\"days\":[{\"num\":\"1\",\"date\":\"2017-8-1\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"2\",\"date\":\"2017-8-2\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"3\",\"date\":\"2017-8-3\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"4\",\"date\":\"2017-8-4\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"5\",\"date\":\"2017-8-5\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"6\",\"date\":\"2017-8-6\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"7\",\"date\":\"2017-8-7\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"8\",\"date\":\"2017-8-8\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"9\",\"date\":\"2017-8-9\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"10\",\"date\":\"2017-8-10\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"11\",\"date\":\"2017-8-11\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"12\",\"date\":\"2017-8-12\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"13\",\"date\":\"2017-8-13\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"14\",\"date\":\"2017-8-14\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"15\",\"date\":\"2017-8-15\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"16\",\"date\":\"2017-8-16\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"17\",\"date\":\"2017-8-17\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"18\",\"date\":\"2017-8-18\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"19\",\"date\":\"2017-8-19\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"20\",\"date\":\"2017-8-20\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"21\",\"date\":\"2017-8-21\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"22\",\"date\":\"2017-8-22\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"23\",\"date\":\"2017-8-23\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"24\",\"date\":\"2017-8-24\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"25\",\"date\":\"2017-8-25\",\"week\":\"5\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"26\",\"date\":\"2017-8-26\",\"week\":\"6\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"27\",\"date\":\"2017-8-27\",\"week\":\"0\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"28\",\"date\":\"2017-8-28\",\"week\":\"1\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"29\",\"date\":\"2017-8-29\",\"week\":\"2\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"30\",\"date\":\"2017-8-30\",\"week\":\"3\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"},{\"num\":\"31\",\"date\":\"2017-8-31\",\"week\":\"4\",\"price\":398,\"is_buy\":\"1\",\"is_select\":\"0\",\"set\":\"10\"}]}]}";

    //TODO 模拟请求数据
    new Timer().schedule(new TimerTask() {
        @Override
        public void run() {
            Type cvbType = new TypeToken<MonthDayBean>(){}.getType();
            MonthDayBean bean = new Gson().fromJson(testStr, cvbType);
            final ArrayList<MonthDayBean.MonthBean> months = bean.getDatas();

            runOnUiThread(new Runnable() {
                @Override
                public void run() {
                    /**1.设置数据，将解析好的数据绑定到控件*/
                    cal_layout.setData(months);
                }
            });

        }
    },500);


    /**2.获取选中日期*/
    public void getResult(View v){
        //得到选中的日期对象集合，注意，此集合中包含离店日期，按道理离店日期不算入住的
        ArrayList<MonthDayBean.Day> selected = cal_layout.getSelectedData();
        if(selected==null || selected.size()<=0){
            ((TextView)(findViewById(R.id.tv_result))).setText("未选中");
            return;
        }
        //移除最后一个离店日期，则是真正的预订酒店的日期
        selected.remove(selected.size()-1);
        String text = "选中入住日期为：\n";
        for(MonthDayBean.Day day : selected){
            text += (day.getDate()+" \n");
        }
        ((TextView)(findViewById(R.id.tv_result))).setText(text);

    }

```


2.图片替换：
>
    修改月份左右箭头：
    res/drawable-xhdpi:
    custom_calendar_row_left.png
    custom_calendar_row_right.png
    修改已租、选中、不可选三种状态下背景
    res/drawable-xhdpi:
    bg_out.9.png          //已租
    bg_select.9.png       //选中
    bg_unclick.9.png      //不可选

    入住日期、离店日期气泡背景：
    res/layout/calendar_layout.xml中修改ll_pop_start&calendar_shape_pop的background属性：
    calendar_shape_pop.xml
    取消选择的红叉叉图片：
    icon_calendar_cancel.png

3. 修改日历上文字大小、文字颜色、间隔值等请参考:
com.hotel.calendar.CustomCalendar类中的：
```Java
    /**星期栏字体颜色设置*/
    private int tc_week = Color.parseColor("#9e9e9d");
    /**日期文字各种状态下的文字颜色*/
    private int tc_day_before= Color.parseColor("#a9a9a9");    //过期(今天之前)
    private int tc_day_out= Color.parseColor("#808080");       //已租
    private int tc_day_click = Color.parseColor("#000000");    //可点击
    private int tc_day_unclick = Color.parseColor("#696969");  //不可点击
    private int tc_day_select = Color.parseColor("#ffffff");   //选中
    /**价格各种状态下文字颜色*/
    private int tc_money_out= Color.parseColor("#808080");       //已满
    private int tc_money_click = Color.parseColor("#000000");      //可点击
    private int tc_money_unclick = Color.parseColor("#696969");  //不可点击
    private int tc_money_select = Color.parseColor("#ffffff");     //选中
    /**字体大小设置*/
    private float ts_week = 13;   //星期栏字体大小
    private float ts_day = 12;    //日期字体大小
    private float ts_money = 10;  //价格字体大小

    /**间距设置dip单位*/
    private int weekSpac = 8;   //星期栏下面的空隙
    private int lineSpac = 3;   //日历行间距
    private int lieSpac = 3;    //日历列间距
    private int textSpac = 0;   //日期与价格之间的距离
    private int textPad = 3;    //日历item中字体与背景上下的间隙
```

4. 修改日历与屏幕左右的间隔：
res/layout/calendar_layout.xml中找到下面的代码，然后修改layout_marginLeft & layout_marginRight：
```xml
<com.hotel.calendar.CustomCalendar
        android:id="@+id/cal"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginLeft="20dp"
        android:layout_marginRight="20dp"
        android:layout_below="@+id/ll_top"/>
```


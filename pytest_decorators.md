1. `@pytest.fixture`: Bir işlevi bir testte kullanılabilir bir kaynak haline getirir.
2. `@pytest.mark.parametrize`: Bir test fonksiyonunu birden fazla girişle çalıştırmak için kullanılır.
3. `@pytest.mark.skip`: Belirli bir testin geçici olarak atlanmasını sağlar.
4. `@pytest.mark.skipif`: Belirli bir koşul karşılandığında bir testin atlanmasını sağlar.
5. `@pytest.mark.xfail`: Bir testin başarısız olmasını beklediğinizi belirtir.
6. `@pytest.mark.timeout`: Bir testin belirli bir süre içinde tamamlanmasını bekler.
7. `@pytest.mark.filterwarnings`: Belirli bir test veya test modülünde üretilen uyarıları kontrol etmek için kullanılır.
8. `@pytest.mark.usefixtures`: Bir test fonksiyonuna önceden tanımlanmış bir fixture'ı eklemek için.
9. `@pytest.mark.parametrize_with_cases`: Birden fazla parametre setiyle aynı testi çalıştırmak için farklı bir kullanım.
10. `@pytest.mark.dependency`: Testler arasında bağımlılıkları belirtmek için.
11. `@pytest.mark.dependency(depends=["test_function"])`: Belirli bir testin başka bir testten önce çalışmasını sağlamak için.
12. `@pytest.mark.slow`: Yavaş testleri işaretlemek için.
13. `@pytest.mark.parametrize_plus`: PyTest'in varsayılan parametrize decorator'ının genişletilmiş versiyonu.
14. `@pytest.mark.parametrize("input", [value1, value2, ...])`: Tek parametreli parametrize örneği.
15. `@pytest.mark.usefixtures("fixture_name")`: Bir test fonksiyonuna fixture'ı eklemek için.
16. `@pytest.mark.flaky`: Zaman zaman başarısız olan testleri belirtmek için.
17. `@pytest.mark.needfiles`: Dosya girişi gerektiren testleri belirtmek için.
18. `@pytest.mark.run`: Bir testin belirli koşullar altında çalışmasını sağlamak için.
19. `@pytest.mark.run(order=N)`: Test sırasını belirlemek için.
20. `@pytest.mark.external_api`: Harici bir API'ye bağlı olan testleri işaretlemek için.
